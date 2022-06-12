1. Shape (in the numpy context) seems to me the better option for an argument name. The actual relation between the two is size = np. prod(shape) so the distinction should indeed be a bit more obvious in the arguments names. randint uses the size parameter name, but uses shape in the explanation.

2.The term broadcasting refers to the ability of NumPy to treat arrays of different shapes during arithmetic operations. Arithmetic operations on arrays are usually done on corresponding elements. If two arrays are of exactly the same shape, then these operations are smoothly performed.

3.It can take data formats of CSV or TSV files, or a SQL database and convert it into Python data frames with rows and columns which is similar to tables in statistical formats. The package makes comparisons with dictionaries with the aid of 'for' loops which are very easy to understand and operate.

4.NumPy introduces a simple file format for ndarray objects. This . npy file stores data, shape, dtype and other information required to reconstruct the ndarray in a disk file such that the array is correctly retrieved even if the file is on another machine with different architecture.

5.The empty() function is used to create a new array of given shape and type, without initializing entries. Shape of the empty array, e.g., (2, 3) or 2. Desired output data-type for the array, e.g, numpy. int8.
