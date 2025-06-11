# 📌 Queue Implementation (`clsMyQueueArr`) ⚡

A C++ template-based queue implementation using a dynamic array (`clsDynamicArray`), supporting basic queue operations along with advanced functionalities. 🚀

---

## 🌟 Project Overview

The `clsMyQueueArr` class provides a **generic queue implementation in C++**, leveraging the `clsDynamicArray` class for dynamic memory management and flexible queue operations. It supports standard queue behavior like enqueue (Push), dequeue (Pop), and peek operations (Front & Back), along with powerful list-style functionalities such as insertions, updates, and reversal.

This makes it perfect for educational purposes, data structure experiments, and customized queue-based systems.

---

## 🔹 Core Functionalities:

- 🚀 Enqueue (Push) & Dequeue (Pop)
- 🔍 Access Front & Back Elements
- 📏 Check Queue Size & Emptiness
- 🔄 Reverse Queue Elements
- ✏️ Modify & Insert Elements Within Queue
- ✨ Clear the Queue in One Call

This queue implementation is **generic**, meaning it can store any data type using **C++ templates**.

---

## ✨ Features

### 🔹 Basic Queue Operations
- `Push(Value)` – Adds an element to the back of the queue.
- `Pop()` – Removes the front element from the queue.
- `Front()` – Retrieves the front element of the queue.
- `Back()` – Retrieves the last element of the queue.
- `Size()` – Returns the number of elements in the queue.
- `IsEmpty()` – Checks if the queue is empty.
- `Print()` – Displays the queue elements.

### 🔹 Extended Functionalities
- `GetItem(Index)` – Retrieves the value at a specific index.
- `Reverse()` – Reverses the order of queue elements.
- `UpdateItem(Index, NewValue)` – Updates the value at a given index.
- `InsertAfter(Index, Value)` – Inserts an element after a specified index.
- `InsertAtFront(Value)` – Inserts an element at the front of the queue.
- `InsertAtBack(Value)` – Inserts an element at the back of the queue.
- `Clear()` – Removes all elements from the queue.

---

## 🚀 How It Works

### 🔹 Push & Pop
- `Push()` adds elements to the **end** of the queue.
- `Pop()` removes elements from the **front** of the queue.

### 🔹 Accessing Elements
- `Front()` and `Back()` provide direct access to boundary elements.
- `GetItem(Index)` supports accessing elements by index (non-standard for queues).

### 🔹 Modifications & Reversal
- `UpdateItem(Index, NewValue)` modifies an element in-place.
- `Reverse()` reverses the entire queue order.
- `InsertAfter()`, `InsertAtFront()`, and `InsertAtBack()` provide additional insertion capabilities.

### 🔹 Memory Management
- The underlying `clsDynamicArray` ensures memory is allocated and freed efficiently.
- `Clear()` resets the queue completely, preventing memory leaks.

---

## 📚 Potential Enhancements

- 🏗 **Iterator Support** – For STL-like traversal.
- ⏳ **Time Complexity Optimization** – For large data handling.
- 🗃️ **Persistent Storage** – Save/load queue data from files.
- 🚀 **Thread Safety** – For multithreaded environments.

---

## ⚙️ Technologies Used

- **Language**: C++
- **Templates**: Enables type-generic queue
- **Dynamic Array**: Backed by `clsDynamicArray`
- **Memory Management**: Efficient and manual control over memory

---

## 🎯 Learning Outcomes

✅ Mastering custom queue implementation  
✅ C++ template programming  
✅ Dynamic array manipulation  
✅ Enhanced data structure operations beyond basic queue logic

---

## 📜 License

This project is open-source. Feel free to use, share, and enhance it! 🚀

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or have an idea for a feature, feel free to fork the repo and submit a Pull Request.

---

## 🏁 Ready to Explore?

### 🚀 How to Run

1. 📥 Download or clone the repository:
   ```bash
   git clone https://github.com/your-username/clsMyQueueArr-CPP.git
   cd clsMyQueueArr-CPP
``
2. 🛠 Include in your project:
```bash
#include"clsMyQueueArr.h" 
#include"clsDynamicArray.h"
```
3. 🧪 Compile and run using a C++ compiler:

```bash
g++ main.cpp -o app
./app
```

