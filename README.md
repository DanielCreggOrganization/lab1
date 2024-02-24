# Lab: Introduction to 2D Arrays in Java

## Objective

In this one-hour lab, we will explore the concept of 2D arrays in Java. We will learn how to declare, initialize, manipulate, and print 2D arrays.

## Introduction

A 2D array in Java is an array of arrays. It is also known as a matrix. Each element of a 2D array is an array itself. This structure allows us to store data in a tabular format.

## Part 1: Declaration and Initialization

### Demo 1

Here is a simple example of how to declare and initialize a 2D array in Java.

```java
int[][] matrix = new int[3][3]; // a 3x3 matrix
```

We can also initialize the 2D array with some values.

```java
int[][] matrix = {
    {1, 2, 3},
    {4, 5, 6},
    {7, 8, 9}
};
```

### Exercise 1

1. Declare and initialize a 2D array with your own values.

## Part 2: Manipulation

### Demo 2

We can manipulate the elements of a 2D array just like a 1D array.

```java
matrix[0][0] = 10; // change the first element
```

### Exercise 2

1. Change the value of the second element in the second row of your array.

## Part 3: Printing

### Demo 3

We can print a 2D array using nested for loops.

```java
for (int i = 0; i < matrix.length; i++) {
    for (int j = 0; j < matrix[i].length; j++) {
        System.out.print(matrix[i][j] + " ");
    }
    System.out.println();
}
```

### Exercise 3

1. Print your 2D array.

## Part 4: Advanced Manipulation

### Demo 4

We can also perform more complex operations on 2D arrays, like finding the sum of all elements.

```java
int sum = 0;
for (int i = 0; i < matrix.length; i++) {
    for (int j = 0; j < matrix[i].length; j++) {
        sum += matrix[i][j];
    }
}
System.out.println("Sum: " + sum);
```

### Exercise 4

1. Write a method that takes a 2D array as a parameter and returns the sum of all elements in the array.

## Conclusion

In this lab, we have learned about 2D arrays in Java. We have seen how to declare, initialize, manipulate, and print them. We have also written a method to perform a complex operation on a 2D array.

## Next Steps

For further practice, try to solve some problems involving 2D arrays on online coding platforms.

Happy coding!
