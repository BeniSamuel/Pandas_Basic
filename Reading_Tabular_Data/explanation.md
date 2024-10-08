### Reading 

**Meaning** : reading means that you are going to read or interpret or view the dataframe which you created.

## Methods used for reading 
- **read_\***: you use the read method and add the form of the thing which you are going to read
  for example:
  ```
  import pandas as pd

  titanic_dataframe_csv = read.csv("titanic.csv")
  titanic_dataframe_excel = read.excel("titanic.xlsx")
  ```

## Reading a column (serie)

As explained in the serie section to read a serie (column) you use the following syntax:

- `` titanic_dataframe_csv["Age"] `` **note** : the column is case sensitive make sure if the column is uppercase you use uppercase

  ## Let's make some cool things on serie

  - let's select based on age greater than 35 ``ageLarge35 = titanic[titanic_dataframe_csv["Age"] > 35]`` **note** : here the ageLarge35 will contain the information about the people where only age is greater than 35

  - let's also try to select age less than 35 ``ageLess35 = titanic[titanic_dataframe_csv["Age"] <35]`` **note** : here the ageLess35 will contain the information about the people where only age is less than 35
   