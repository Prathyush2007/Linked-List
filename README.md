# Linked List  

**Name:** Prathyush  
**PRN:** 24070123064  
**Batch:** ENTC A3  

---

## 📌 Overview  

A **Linked List** in C++ is a dynamic data structure that connects data elements (nodes) using pointers. Unlike arrays, linked lists do not need continuous memory, making insertion and deletion more efficient.  

Each **node** has two parts:  
- **Data** → Stores the element.  
- **Pointer (next)** → Refers to the next node in the sequence.  

### 🔹 Types of Linked Lists  
- **Singly Linked List** → Node links only to the next node.  
- **Doubly Linked List** → Node links to both previous and next nodes.  
- **Circular Linked List** → The last node connects back to the first.  

In this README, we demonstrate **basic operations on a singly linked list**:  
1. Adding nodes at the end.  
2. Adding nodes at the start.  
3. Creating a single node.  

---

## 1️⃣ Add Multiple Nodes at the End of the Linked List  

### 🔹 Algorithm  
1. Define a `Node` class with `val` and `next`.  
2. Define a `LinkedList` class with `head = NULL`.  
3. To insert at the end:  
   - Create a node.  
   - If the list is empty, set it as `head`.  
   - Otherwise, move to the last node and connect it.  
4. To display, start from `head` and print values until the end.  

### 🔹 Theory  
This program adds elements by linking them at the end.  
- The first element becomes the head.  
- Each new element is connected after reaching the last node.  
- The `display` function prints values in sequence.  

### ✅ Output  
Linked List: 10 20 30 40


---

## 2️⃣ Add Multiple Nodes at the Start of the Linked List  

### 🔹 Algorithm  
1. Define a `Node` class with `data` and `next`.  
2. To insert at the start:  
   - Create a node.  
   - Link its `next` to the current head.  
   - Update head to this new node.  
3. To display, traverse from `head` printing each value.  

### 🔹 Theory  
This program inserts nodes at the **beginning** of the list.  
- Each new element becomes the new head.  
- Existing elements shift forward as new nodes are added.  

### ✅ Output  


30->NULL
32->30->NULL
35->32->30->NULL


---

## 3️⃣ Single Node of the Linked List  

### 🔹 Algorithm  
1. Define a `Node` class with `val` and `next`.  
2. Use dynamic allocation (`new`) to create a node.  
3. Store a value and set `next = NULL`.  
4. Print the node’s data and pointer.  

### 🔹 Theory  
This program builds a **single node** of a linked list.  
- The node stores a value (`20`) and its pointer is `NULL`.  
- It is the base element used to form larger linked lists.  

### ✅ Output 
20 0


---
