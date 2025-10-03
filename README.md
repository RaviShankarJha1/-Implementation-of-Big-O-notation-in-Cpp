# Implementation-of-Big-O-notation-in-CPP  

## Aim  
To study and implement Big O notation in C++.  

## Software Required  
- Mingw C/C++ Compiler  
- Visual Studio Code  
- Online C++ Compiler  

## Program Time Complexity  

### Theory  
Time complexity measures how the runtime of an algorithm grows with input size.  

- **O(1)** → Constant time: Execution does not depend on input size.  
- **O(n)** → Linear time: Execution scales directly with input size.  
- **O(n²)** → Quadratic time: Execution scales with the square of input size.  

**Examples in code:**  
- `getFirstElement()` → Demonstrates **O(1)** by accessing a single element.  
- `printElements()` → Demonstrates **O(n)** by printing each element once.  
- `printPairs()` → Demonstrates **O(n²)** by printing all possible pairs.  

These examples help visualize how performance changes with input growth.  
Understanding time complexity is crucial for writing efficient code and guides algorithm selection based on data size and performance needs.  

## Algorithm  

1. Start  
2. Define a vector with sample integers.  
3. Call a function to return the first element (**O(1)**).  
4. Call a function to print all elements (**O(n)**).  
5. Call a function to print all element pairs (**O(n²)**).  
6. Display the output for each case.  
7. End  

## Conclusion  
This program effectively illustrates how different time complexities behave.  
- **O(1)** is fastest and ideal for direct access.  
- **O(n)** is manageable for moderate data.  
- **O(n²)** becomes costly as input grows.  

Recognizing these patterns helps developers optimize algorithms and make informed design choices for scalable applications.
