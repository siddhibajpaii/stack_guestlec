#Program 1: Aim: To implement a stack data structure using an array in C++ that supports basic operations like push, pop, and display, demonstrating the Last-In-First-Out (LIFO) behavior of stacks.

Thoery: The program implements a simple stack data structure using an array with a fixed size of 5 elements. A stack follows the Last-In-First-Out (LIFO) principle, meaning the most recently added item is the first to be removed. The Stack class has private members: an integer array to hold the stack elements and an integer top to track the index of the current top element. The push method adds an element to the top of the stack by incrementing top and assigning the new value. The pop method removes the top element by decrementing top. The display method attempts to print the elements of the stack, but there is a small bug in the loop which causes it to print the top element multiple times instead of all elements. Overall, the code demonstrates basic stack operations but can be improved by adding boundary checks and correcting the display logic.

Algorithm:

    Step-1: Start
    Step-2: Increment the top index by 1.  
    Step-3: Insert the new element at arr[top].
    Step-4: Decrement the top index by 1, effectively removing the top element from the stack.
    Step-5: Iterate from index 0 to top.
    Step-6: Print each element in the stack.
    Step-7: End.

#Program 2: Aim: To demonstrate the use of a stack to perform simple arithmetic operations (addition and multiplication) on integers using the standard stack operations push, pop, and top.

Theory: This C++ program uses the STL stack to perform basic arithmetic computations. The program pushes integers onto the stack, pops them to retrieve values, performs addition and multiplication operations, and pushes the results back onto the stack. Finally, it outputs the computed result. The program showcases how stacks can be used to handle temporary data and intermediate calculations in a Last-In-First-Out (LIFO) manner.

Alogorithm:

    Step-1: Start
    Step-2: Initialize an empty stack of integers.
    Step-3: Push the integer 1 onto the stack.
    Step-4: Push the integer 2 onto the stack.
    Step-5: Pop the top two elements (2 and 1), add them, and push the sum (3) back onto the stack.
    Step-6: Push the integer 3 onto the stack.
    Step-7: Pop the top two elements (3 and 3), multiply them, and push the product (9) back onto the stack.
    Step-8: Output the top element of the stack, which is the final result.
    Step-9: End.

#program 3: Aim: To implement and demonstrate the linear search algorithm on a vector of integers to find the presence and index of a given key element.

Theory: This C++ program defines a class SearchAlgorithms that contains a method linearSearch to perform a linear search on a vector of integers. The program takes a vector and a key element as input, iterates through the vector elements sequentially, and checks if the key is present. If found, it prints the index of the key; otherwise, it indicates that the element was not found. The program demonstrates a basic search technique useful for unsorted data.

Algorithm:

    Step-1: Start
    Step-2: Define a vector containing integer elements.
    Step-3: Define the key element to search for.
    Step-4: Traverse the vector from the first element to the last:
    Step-5: At each iteration, check if the current element matches the key.
    Step-6: If yes, print the index where the element is found and exit the search.
    Step-7: If the entire vector is traversed without finding the key, print "Element not found."
    Step-8: End.
