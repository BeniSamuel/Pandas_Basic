## Creating a Data Frame with Pandas

**Data Frame** : is like the table which we are making as you know pandas allow us to work with file which contains things
like table so pandas is good at that and in this case this is referred to as data frame

### Creating a Data Frame Steps with Pandas

**Step 1**: `import pandas as pd` (for allowing you to work with that table structure)
**Step 2**: use the **DataFrame** method returned by this pd for creating the table
for example: `pd.DataFrame({ "name":[dataOne,dataTwo], "age":[dataThree,dataFour] })`

  **note** : in the above example the DataFrame method provide you with an object where you specify the structure of the table
  using python dictionaries where keys are the column and the values cause they are many it is the list of values used in this case

**Step 3**: After creating the structure of the table you can store in the variable 
for example :  `df = pd.DataFrame({ "name":[dataOne,dataTwo], "age":[dataThree,dataFour] })`

**Step 4**: Now you can print it and see the output
`print(df)`

**Step 5**: Full Code View

`import pandas as pd`
`df = pd.DataFrame({ "name":[dataOne,dataTwo], "age":[dataThree,dataFour] })`
`print(df)`