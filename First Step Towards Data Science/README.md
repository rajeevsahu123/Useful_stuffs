# First-Step-Towards-Data-Science
Basic information for those who are looking for data science as a career

Trying to make an exhaustive material that will help you to learn and practise on different datasets

https://www.analyticsvidhya.com/learning-paths-data-science-business-analytics-business-intelligence-big-data/learning-path-data-science-python/

1. Basics of Python

    Data Types: Int, Bool, Float, String
    
    Data Structures: List, Sets, Tuples, Dictionary
    
    Arithmetic Operators: +, -, *, **, /
    
    Compariosn Operators:
    
    == Equal to 
    
    != Not equal to
    
    &gt;= Greater than equal to
    
    <= Less than equal to
    
    < less than
    
    &gt; Greater than
    
    
    Control Operators: if statement
    
    Creation a Function:
    
    def mysum(a,b):
    
      return a+b
    
    Temporary / Lambda Function: 
    
      mysum=lambda a, b: a+b
    
    List Comprehension:
    
    [x for x in range(5) for x%%2 = 0]
  
2. Data handling in Python: 

    Numpy: arrays
    
    Pandas: Series (1D array), DataFrame (2D array)
    
    Import Data: pd.read_csv(). pd.read_excel()
    
    df.head(), df.tail(), df.describe(), df.info()
    
    Indexing methods: df.iloc (integer based), df.loc (label based)
    
    df['Variable Name'].value_counts()
    
    Missing Value treatment: df.dropna(), df.fillna(), df.isnull(), df.notnull()
    
    Creating dummy variables: pd.get_dumimies
    
    Concatenation of tables: pd.concat
    
    Merge Tables: pd.merge (Types of join: Innerjoin, outer join, right join, left join)
    
    Pivot Table: pd.pivot_table()

    Drop variables: df.drop('Variable Name', inplace=True) or del df['Variable Name']
