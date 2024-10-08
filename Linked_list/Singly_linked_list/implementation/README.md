# Singly Linked List

## Definition:

A **singly linked list** is a type of data structure that consists of a sequence of elements called nodes, where each node contains two parts:

1. **Data**: The value or information stored in the node.
2. **Next Pointer**: A reference (or pointer) to the next node in the sequence.

In a singly linked list:

* The first node is called the **head**, and it serves as the entry point of the list.
* The last node points to **null (or None)**, indicating the end of the list.
* The nodes are connected in a one-way direction, meaning you can traverse the list only in a forward direction.

## Structure of a Node:

Each node in a singly linked list contains:
- **Data**: Stores the actual data value.
- **Next**: A pointer to the next node in the list.

## Operations on Singly Linked List

Some common operations performed on a singly linked list include:

* **Insertion**: Adding a new node to the list (at the beginning, end, or specific position).
* **Deletion**: Removing a node from the list (by value or by position).
* **Traversal**: Visiting each node in the list from the head to the end.
* **Searching**: Finding a specific node in the list by its value.
* **Reversal**: Reversing the order of the nodes in the list.

## Advantages of Singly Linked List

* **Dynamic Size**: The size of the list can grow or shrink dynamically as elements are added or removed.
* **Efficient Insertion/Deletion**: Inserting or deleting elements from the beginning or middle of the list is more efficient compared to arrays (no need to shift elements).

## Disadvantages od Singly Linked List

* **No Backward Traversal**: You cannot traverse the list in reverse, unlike doubly linked lists.
* **Memory Usage**: Each node requires extra memory for storing the pointer to the next node.
