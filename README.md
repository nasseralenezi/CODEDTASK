# Manipulating Data Task using pandas library in Python

pandas is one of the most popular libraries in Python which is commonly used among data scientists. It helps us to organize 📑, clean 🧹, and analyse 🧐 the data.

One cleaning mechanism is manipulating data, and a good example is dropping unnecessary columns or rows


## Where to start?

In order to use pandas library, it needs to be called by importing it

```python
import pandas
```

and most of the time we call it as "**pd**" for quick reach

```python
import pandas as pd
```

## What we know?

pandas has a data structure that has two axes (rows and columns).

![table](https://i.ibb.co/2dz4CCF/Untitled-2.png)


## Basic Requirements

This data structure is called Dataframe, so let's create a Dataframe which has countries and some of their cities

```python
df = pd.DataFrame(
{"Kuwait" : ['Jahra', 'Hawalli', 'Kayfan'],
"Saudi" : ['Riyadh', 'Makkah', 'Jeddah'],
"USA" : ['Los Angeles', 'New York', 'Chicago ']})

df
```
which will give the following results

|   | Kuwait | Saudi | USA |
| ----------- | ----------- | ----------- | ----------- |
| 0 | Jahra | Riyadh | Los Angeles |
| 1 | Hawalli | Makkah | New York | 
| 2 | Kayfan | Jeddah | Chicago | 


now go to [pandas cheat sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf) and look at the **Reshaping Data** section and do the following:

- Drop the last column, so we only keep Arab countries
- Rename the second column to "Saudi Arabia"


The table should look like this after doing the task

|   | Kuwait | Saudi Arabia |
| ----------- | ----------- | ----------- |
| 0 | Jahra | Riyadh | 
| 1 | Hawalli | Makkah | 
| 2 | Kayfan | Jeddah | 
