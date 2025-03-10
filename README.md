# Python-Pandas
Pandas has 2 two types of Data structure
1. Series - one dimensional array with indexes
2. DataFrame - Tabular spreadsheet
Pandas - List,Dict,tupple

In python
axis = 1 -- (column)
axis = 0 -- (row)


1. df.to_csv('family.csv') --- It will craete new csv file in same folder and add DF data into it

2. df.to_csv('family_index_false.csv',index = False) -- it will remove index of table data

3. df.head(2) --it will print 1st 2 rows of table data

4. df.tail(2) --it will print last 2 rows of table data

5. df.describe() --- shows statistical analysis like count,mean,max,75%,25%,50%,std

6. Book['BookPublishyear'][0]  --- it will shows value of 1st index

7. Book['BookPublishyear'][0] = 2025 -- It will replace the new value with existing one

8. Book.to_csv('BookList.csv') -- After changes/modification into DataTable value replace with new data , it will create new csv file with the same name

9. Book.index = ['first','second','Third','Fourth','Fifth']  -- Index no will change Int to charcater for eg.1 - one,2 - Two , etc

10. newdf[0][0] = "Test" -- changed datatype and value u=int to string

11. newdf.T  -- Transpose (total no of rows changed to column and column wil chane into rows)

12. newdf2 = newdf -- it will not create or  copy of newdf data to newdf2.It will only create the view for this

13.newdf2 = newdf.copy()

14. newdf.columns = list("ABCDE") -- naming index of column  instead of 0,1,2,3,4,  to A,B,c,D,E

15. newdf.loc[[1,2],['C','D']] -- fetch 1st 2 rows and C and D column data(Matrix form)

16. newdf.loc[[1,2],:] -- fetch 1st 2 rows with all columns,we should give exact indx name

17. newdf.iloc[0,4]  -- it will return the value of Oth row and 4th column of data

18. newdf.drop(['A','D'], axis = 1) -- It will drop A and D column but original dataframe will b same as it is return the copy of dataset

19.  newdf.drop(['A','D'], axis = 1, inplace = True) -- it will modify original table.

20.  newdf.reset_index() -- It will reset index start from 0 but it will add column as Index 

21.  newdf.reset_index(drop = true) -- it will drop 1st column name as index

22.  newdf.dropna(inplace = True) -- It will drop null values

23.  df.dropna(how = 'all',axis = 1) -- it will delete wholw column  as all rows having NaN values

24.  df.drop_duplicates(subset = ['name']) -- remove duplicate value

25.  df['name'].value_counts(dropna=False) -- it will give the count of values and it not delete na values as well

26.  














