# Btexl-Queue-Project

# Queue Implementation in C

## Description
This project is a simple implementation of a queue data structure in C using dynamic memory allocation. It allows the user to perform basic queue operations such as enqueue (push), dequeue (pop), peek, checking if the queue is empty or full, and printing elements.

## Features
- Dynamically allocated queue
- User-defined queue capacity
- Operations:
  - Enqueue (Push)
  - Dequeue (Pop)
  - Peek (View front element)
  - Check if the queue is empty or full
  - Get the size of the queue
  - Print all elements in the queue
- Interactive menu-based interface

## Prerequisites
- A C compiler (GCC, Clang, or MSVC)

## Compilation and Execution
To compile the program, use the following command:
```sh
gcc queue.c -o queue
```
To run the program:
```sh
./queue
```

## Usage
1. Enter the capacity of the queue when prompted.
2. Choose an option from the menu:
   - `1` to enqueue an element
   - `2` to dequeue an element
   - `3` to peek at the front element
   - `4` to get the size of the queue
   - `5` to check if the queue is empty
   - `6` to check if the queue is full
   - `7` to print all elements
   - `8` to exit the program

## Example
```
Enter the capacity of the queue: 5

Menu:
1. Enqueue (Push)
2. Dequeue (Pop)
3. Peek
4. Size
5. Is Empty
6. Is Full
7. Print Elements
8. Exit
Enter your choice: 1
Enter value to enqueue: 10
Enqueued element: 10
```

## Memory Management
- The queue is dynamically allocated using `malloc`.
- Memory is freed before exiting the program to prevent memory leaks.

## Limitations
- The implementation uses a static array with a fixed capacity.
- Does not implement a circular queue.

## Future Improvements
- Implement a circular queue to optimize memory usage.
- Use linked lists for dynamic queue expansion.
- Add error handling for invalid inputs.

## License
This project is open-source and free to use under the MIT License.

