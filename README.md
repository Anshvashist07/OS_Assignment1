# Operating Systems Lab Assignment

This repository contains solutions for **Lab Assignment-1** of the Operating Systems course.  
All tasks are implemented in **Python**, using the built-in **`os` module** and process management concepts.

---

## 📌 Assignment Details
- **Student Name:** Ansh Vashist  
- **Roll Number:** 2301420019  
- **Experiment Title:** Process Creation and Management Using Python OS Module  

---

## 🧪 Tasks Implemented

### **Task 1: Process Creation Utility**
- Demonstrates how to create new processes in Python using the `os.fork()` and `os.getpid()` functions.
- Shows the relationship between parent and child processes.

---

### **Task 2: Command Execution Using `exec()`**
- Executes system-level commands using Python’s `os.exec*()` family of functions.
- Demonstrates replacing the current process image with a new one.

---

### **Task 3: Zombie & Orphan Processes**
- Illustrates how zombie and orphan processes are created.
- Demonstrates proper handling of child processes to avoid zombies using `os.wait()`.

---

### **Task 4: Inspecting Process Info from `/proc`**
- Reads process-related information from the **`/proc` filesystem** (Linux).
- Displays PID, status, and other details of running processes.

---

### **Task 5: Process Prioritization**
- Demonstrates setting process priorities using `os.nice()` and other system calls.
- Explains how different priority levels affect CPU scheduling.

---

## ⚙️ Requirements
- Python 3.x  
- Linux/Unix-based system (for `/proc` and process management to work)  

---
