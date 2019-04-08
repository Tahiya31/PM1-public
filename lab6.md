# Lab-6
Operator overloading syntax


## Problem 1
Write a Matrix class, that holds an matrix of doubles,  and overwrite the copy constructor, addition(+), subtraction(-),  multiplication(\*).

```
Matrix M(3,3);
Matrix N(3,2);

K=M*N;
A=M*M;
B=M-M;
```

## Problem 2
Implement the transpose function and use it for doing matrix multiplication.

```
Matrix M(3,3);
Matrix N(2,3);

K=M*N';
A=M*M;
B=M-M;
```

## Problem 3 (extra credit problem)
Overload the input and output stream operators to display the Matrix and to populate a Matrix from cin;


```
INPUT: 1 2 3; 1 4 5; 1 1 9
OUTPUT:
1 2 3
1 4 5
1 1 9
```

