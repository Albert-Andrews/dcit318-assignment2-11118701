# DCIT 318 - Assignment 2

**Name:** Quaye Andrews Albert Awuley  
**Student ID:** 11118701  
**Course:** DCIT 318 - Programming II  
**GitHub Repository:** [dcit318-assignment2-11118701](https://github.com/YourUsername/dcit318-assignment2-11118701)

---

## 📌 Overview
This repository contains three separate C# console applications demonstrating different aspects of **Object-Oriented Programming (OOP)** in C#:

1. **Inheritance & Method Overriding**
2. **Abstract Classes & Methods**
3. **Interfaces**

---

## 📂 Project Structure
```
dcit318-assignment2-11118701/
│
├── Task1-Inheritance/
│   └── Program.cs
│
├── Task2-AbstractClasses/
│   └── Program.cs
│
├── Task3-Interfaces/
│   └── Program.cs
│
└── README.md
```

---

## 📝 Task Details

### 1️⃣ Inheritance & Method Overriding
- **Base Class:** `Animal` → `MakeSound()` prints `"Some generic sound"`.
- **Derived Classes:**
  - `Dog` → Overrides `MakeSound()` to print `"Bark"`.
  - `Cat` → Overrides `MakeSound()` to print `"Meow"`.

### 2️⃣ Abstract Classes & Methods
- **Abstract Class:** `Shape` → Abstract method `GetArea()`.
- **Derived Classes:**
  - `Circle` → Calculates area of a circle.
  - `Rectangle` → Calculates area of a rectangle.

### 3️⃣ Interfaces
- **Interface:** `IMovable` → Method `Move()`.
- **Implementations:**
  - `Car` → Prints `"Car is moving"`.
  - `Bicycle` → Prints `"Bicycle is moving"`.

---

## ▶ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/dcit318-assignment2-11118701.git
   cd dcit318-assignment2-11118701
   ```
2. Navigate to any task folder and run:
   ```bash
   dotnet run --project Task1-Inheritance
   ```

---

## ✅ Expected Outputs

### Task 1:
```
Some generic sound
Bark
Meow
```

### Task 2:
```
Circle Area: 78.53981633974483
Rectangle Area: 24
```

### Task 3:
```
Car is moving
Bicycle is moving
```

---

