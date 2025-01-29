# githubvisual
# Git Visualization Using Stacks

This repository demonstrates how Git works internally using the **Stack** data structure. It provides a simple visualization of how commits, branches, and undo operations function in Git by modeling them as stack operations.

## 🔍 Concept
Git follows a Last-In-First-Out (LIFO) approach in many operations, similar to a **stack**. This project visualizes how commits are pushed onto a stack and popped when rolling back changes.

### 🛠 How Git Relates to Stacks
- **Commits** → Pushed onto the stack.
- **Undo (Revert/Reset)** → Pops the latest commit.
- **Branches** → Represent multiple stacks, allowing diverging paths.
- **Merging** → Combines stacks into a single branch.

## 📌 Features
- Simulates Git operations using a stack.
- Visualizes commit history as a stack.
- Supports undo (pop operation) and redo.
- Demonstrates branching and merging using multiple stacks.

## 🚀 Getting Started
### Prerequisites
- HTML  CSS JAVASCRIPT 
- Basic understanding of Git and Stack data structures

### Installation
Clone this repository:  
```bash
