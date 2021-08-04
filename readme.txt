IR FINAL PROJECT README

    Zip FIle has the following files:
           1)code.py
           2)Batsman_Data.css
           3)readme.txt
           4)Report.pdf
 
pd.read_csv   -   reading a csv file by using pandas function, to perform operations on it also

bd - we consider Batsman_Data.csv file as bd

bd.head() - method is used to return top n (5 by default) rows of a data frame or series. 
            This function returns the first n rows for the object based on position.
             It is useful for quickly testing if your object has the right type of data in it.

bd.dtypes - (an instance of numpy. dtype class) describes how the bytes in the fixed-size block of memory corresponding to an array item should be interpreted.
            It describes the following aspects of the data: 
              Type of the data (integer, float, Python object, etc.)

bd.drop -  It is used to drop specified labels from rows or columns.
            Remove rows or columns by specifying label names and corresponding axis, or by specifying directly index or column names. 
            When using a multi-index, labels on different levels can be removed by specifying the level.

bd_indiviual - It is used to represent the individual performance.

bd.query - It is used to represent some query.

plt.title - The title() method in matplotlib module is used to specify title of the visualization depicted and displays the title using various attributes.

plt-scatter - It is a type of plot that shows the data as a collection of points. 
              The position of a point depends on its two-dimensional value, where each value is a position on either the horizontal or vertical dimension.