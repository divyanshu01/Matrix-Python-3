# Matrix-Python 3 #

###Below is the guide to use the library:###

Import the module in the main python file and create an object of the class "Matrix".The Library is only for square matrices yet and the basic functions that can be performed on non-square matrices will be added soon. The following project uses Python 3.x.

####About files included####
* **Matrix.py** is the main module that is supposed to be imported in the main file.
* **Driver.py** is a driver script used to test the module for its different functionalities.

**Warning**:The work is in progress.
- - - -

* `addMatrix(Matrix obj)`
>The function add the calling instance of `Matrix` to the `Matrix` instance passed as argument and returns the resultant `Matrix` instance.


* `detMatrix()`
>The function returns the determinant value of the matrix if the calling matrix is a square matrix.


* `divScalarMatrix(integer)`
>The function divides the matrix with the scalar which is passed as argument.


* `getMinor(list, integer)`
>The function is used to get the minor matrix of a matrix corresponding to the location of the element. The function is for internal use only and therfore not advisable to be used explicitly.


* `getMinorForCofactor(list, integer, integer)`
>The function is used for determining the minor of a specified element required to calculate the cofactor matrix of a given matrix. The function is for internal use only and therfore not advisable to be used explicitly.


* `inputMatrix()`
>The Function inputs matrix one row at a time, enter the elements seperated by space. The matrix is stored in the form of a nested list where the element list represent a row and the list as a whole in turn represents a 2 dimensional matrix.


* `inverseMatrix()`
>The function returns a `Matrix` which is inverse of the original `Matrix` object.


* `mulMatrix(Matrix obj)`
>The function returns a `Matrix` object which is the multiplied result of the calling object and the object passed as argument.


* `mulScalarMatrix(integer)`
>The function multiplies the matrix with the scalar which is passed as argument. 


* `printMatrix()`
>The function displays the matrix on the screen.


* `subMatrix(Matrix obj)`
>The function returns the `Matrix` instance of the subtraction of the calling `Matrix` instance and the `Matrix` passed as argument.


* `transMatrix()`
>The function turns the matrix into its transpose.
