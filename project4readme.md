# Project 04: SortedLinkedList

## 📌 Project Description
This Java program allows users to input integers one at a time. When the user types `done`, the program sorts the list of integers using Java's built-in `Collections.sort()` and displays the result in ascending order. The program demonstrates dynamic data structures and input handling using Java's `LinkedList`, `Scanner`, and sorting utilities.

---

## 🛠️ How to Compile

```bash
javac SortedLinkedList.java
```

This compiles the Java source file and creates `SortedLinkedList.class`.

---

## ▶️ How to Run

```bash
java SortedLinkedList
```

You'll be prompted to enter numbers one at a time. Type `done` to finish and view the sorted list.

### Example:

```
Input:
5
12
3
done

Output:
Sorted List:
3 5 12
```

---

## 📄 How to Generate Javadoc

```bash
javadoc -d docs SortedLinkedList.java
```

This will generate JavaDoc HTML documentation in a `docs/` folder, including `index.html` and `SortedLinkedList.html`.

---

## 🔁 Code Reuse & Design

This program demonstrates reusable modular design using standard Java components:

- `LinkedList<Integer>` to store user input dynamically
- `Scanner` for input handling
- `Collections.sort()` for sorting the list
- Clean separation of logic in the `main()` method

The program design and UML diagram are detailed in `SortedLinkedListStep5and6.pdf`.

---

## 📁 Files Included

- `SortedLinkedList.java` – Source code
- `SortedLinkedList.class` – Compiled class file
- `README.md` – This documentation file
- `SortedLinkedListStep5and6.pdf` – UML diagram and program explanation
- `docs/` – JavaDoc files generated from the source code
