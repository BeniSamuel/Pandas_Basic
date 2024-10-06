### Serie Operation

**Serie**: is the column in the dataframe as we explained in the first section we said that dataframe is the table and the serie now is the column in the dataframe

## Basic Operation

 - **max** : on the serie you can find the maximum element
   for example:
```
import pandas as pd
studentDFrame = pandas.read_csv("../Creating_DataFrame/sample_two.csv")
studentDFrame["name"].max()
```
 - **min**: on the serie you can find the minimum element
   for example:
```
import pandas as pd
studentDFrame = pd.read_csv("../Creating_DataFrame/sample_two.csv")
studentDFrame["name"].min()
```
