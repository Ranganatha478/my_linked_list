# my_linked_list
This project provides a simple implementation of a singly linked list in C++.It includes basic operations such as:
- Appending and prepending elements
- Deleting elements (first, last, and specific index)
- Retrieving and modifying elements
- Reversing the linked list

Features
- Dynamic memory management: Proper memory deallocation in the destructor.
- Encapsulation: Uses a private head and tail pointer to manage the linked list.
- Ease of use: Simple methods for interacting with the list.
  
How to Use

- Compilation
  To compile the program, use a standard C++ compiler:
  g++ linked_list.cpp -o linked_list
  
- Execution
  Run the compiled executable:
  ./linked_list

- Example Usage
  LinkedList myList(1);
  myList.append(2);
  myList.append(3);
  myList.printList(); // Outputs: 1 2 3

  myList.reverse();
  myList.printList(); // Outputs: 3 2 1


Future Improvements
Possible enhancements include:
- Doubly linked list implementation
- Additional utility functions like sorting
- Iterator support for traversal
  
License
This project is open-source under the MIT License.




