# Templates
A template is a simple yet very powerful tool in C++. 
The simple idea is to pass data type as a parameter so that we don’t need to write the same code for different data types.
We write a generic function that can be used for different data types.
Templates are expanded at compiler time. This is like macros.
The difference is, that the compiler does type checking before template expansion. 
The idea is simple, source code contains only function/class, but compiled code may contain multiple copies of the same function/class. 
