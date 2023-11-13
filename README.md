# abstract_class

Q1
Define a class NumInterface whose only role is to provide a common interface (member function prototypes) for the derived classes. It should provide the functions: display(), increment(). You'll guess the full prototype of each function by what you think would be their functionality in the derived classes. In this abstract class the function bodies would be empty.
There is no point to store any data since we do not know what kind of number we are dealing with. You should make it an abstract class, i.e., it should be impossible to create its object.
Define your class such that the first line in main(), on compilation, produces the error as described in the comments. Once you have successfully produced the compile error, comment that line to pass the test case.

Q2

From the base class NumInterface that you wrote in Q1, derive two more classes with following interfaces: 

1. NumWhole: // this should store the values of whole numbers, choose an appropriate data type as private member!
- NumWhole(val) // constructor
- getval()
- setval()
- display()
- increment() // should increment the stored value and do nothing else
- operator+ // should be able to add two whole numbers using the "+" operator
2. NumComplex: // this should store the values of signed complex numbers, choose appropriate data types to store the real and imaginary parts as private members!
- NumComplex(real, imag) // constructor
// getter // setter
// should display the value and do nothing else.
- getreal()
- setreal()
- getimag()
- setimag()
- display()
- increment() // should increment the stored value (real++, imag++) and do nothing else - operator+ // should be able to add two complex numbers using the "+" operator
The interfaces of the functions (number of args as well as their types + return type) are deliberately missed for you to guess.
The main function given should produce the output as provided in the comments.
