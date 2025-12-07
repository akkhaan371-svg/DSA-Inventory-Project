```markdown
# Game Inventory Manager Using Linked Lists

**Group Members:**  
- Muhammad Haris Habib (62670)  
- Hazrat Ali Khan (63046)  
- Habibullah Naz (63290)  

**Course / Semester:** Data Structures & Algorithms (DSA)  

---

## 1️⃣ Introduction
This project is a simple **Game Inventory Management System** developed in C++.  
It manages different items in a game, such as weapons, potions, or shields.  
The project uses **Linked Lists**, which allow items to be added and removed dynamically without wasting memory.  
This project fulfills **CLO 5.1** because it selects the correct data structure (Linked List) to solve a real-world style problem.

---

## 2️⃣ Problem Statement
In many games, players collect items like weapons, health packs, coins, etc. Managing these items requires a system that can add, remove, and display inventory easily.  
The goal of this project is to create a **simple game inventory manager** using linked lists in C++.  
The system allows players to store items dynamically during gameplay.

---

## 3️⃣ Methodology
**Why Linked Lists:**  
- Allows dynamic memory allocation  
- Items can be added or removed easily  
- Inventory can grow or shrink (no fixed size)  
- Simple and efficient for this type of system  

**Steps Followed:**  
1. Designed a struct/node to store:
   - Item ID  
   - Item Name  
   - Quantity  
   - Pointer to the next node  
2. Wrote functions for:
   - Add Item  
   - Remove Item  
   - Display Inventory  
3. Built a simple menu system for user actions.  
4. Tested the code by:
   - Adding different items  
   - Removing items  
   - Checking output correctness  

---

## 4️⃣ Features
- Add new items to the inventory  
- Remove items by ID  
- Search items by ID  
- Display all items in inventory  
- Menu-driven console interface  
- Uses dynamic memory (linked list)

---

## 5️⃣ Repository Structure

```

DSA-Inventory-Project/
│
├── src/
│   └── inventory.cpp   # Main C++ source code
└── README.md           # Project overview and instructions

````

---

## 6️⃣ How to Compile & Run

```bash
g++ src/inventory.cpp -o inventory
./inventory
````

Follow the on-screen menu to add, remove, search, or display items.

---

## 7️⃣ Data Structure & Implementation

* **Singly Linked List** stores inventory items dynamically.
* Each node contains:

  * `id` (integer)
  * `name` (string)
  * `quantity` (integer)
  * `next` pointer to the next item
* Operations implemented:

  * Add Item: Insert at the end
  * Remove Item: Delete by ID
  * Search Item: Find by ID
  * Display Inventory: Traverse and display all items

---

## 8️⃣ Usage Example

```
===== GAME INVENTORY MANAGER =====
1. Add Item
2. Remove Item
3. Search Item
4. Display Inventory
5. Exit
Enter choice: 1
Enter Item ID: 101
Enter Item Name: Potion
Enter Quantity: 5
Item added successfully!

Enter choice: 4
--- Game Inventory Items ---
ID: 101 | Name: Potion | Quantity: 5
```

---

## 9️⃣ Results

* Program successfully adds new inventory items.
* Items are removed correctly using their ID.
* Full inventory displays in an easy-to-read format.
* Linked list updates dynamically without errors.

---

## 🔟 Conclusion

This project demonstrates how **Linked Lists** can be used to solve real-world problems like managing a game inventory.
The project meets all requirements:

* Problem is clear
* Correct data structure is used
* All functions work properly
* Documentation and explanation are included
* Code runs without errors

The system is **simple, reliable, and fulfills CLO 5.1** by correctly applying a suitable data structure to a problem scenario.

---

## ⚠️ Known Limitations / Notes

* Duplicate IDs are not prevented.
* Items are lost when the program exits (no file storage).
* Simple console interface (no GUI).

```

---

This version now includes:  
- Group member info  
- Full introduction, problem statement, methodology  
- Features, repository structure  
- Compile/run instructions  
- Data structure explanation  
- Usage example  
- Results & conclusion  
- Known limitations  







