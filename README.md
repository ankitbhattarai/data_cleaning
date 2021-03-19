# data_cleaning
1. **<font color="red">Data Set Used</font>** Breast Cancer Dataset https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29 
                 Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the      image.n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].
                 Class distribution: 357 benign, 212 malignant
2. **<font color="red">Missing Values</font>**
            Observe that only the 'Bare Nuclei' column contains missing values. In the following example, the missing values in the 'Bare Nuclei' column are replaced by the median value of that column. The values before and after replacement are shown for a subset of the data points.
            Instead of replacing the missing values, another common approach is to discard the data points that contain missing values. This can be easily accomplished by applying the dropna() function to the data frame.

            
3. **<font color="red">Outliers</font>**
4. **<font color="red">Duplicate Data</font>**
5. **<font color="red">Aggregration</font>**
6. **<font color="red">Sampling</font>**
7. **<font color="red">Discretization</font>**
