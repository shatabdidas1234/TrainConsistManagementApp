
## **Project Procedure – UC7: Sort Passenger Bogies by Capacity**

### **1. Continue the Project**

Using the existing Java project and class **TrainConsistManagementApp.java**, extend the system to **sort passenger bogies based on seating capacity** using custom logic.

---

### **2. Display UC7 Title**

Inside the `main` method, print:

```
=====================================
 UC7 - Sort Bogies by Capacity
=====================================
```

This indicates that sorting functionality is being performed.

---

### **3. Create Bogie Class**

Define a class to represent bogies:

```
static class Bogie {
    String name;
    int capacity;

    Bogie(String name, int capacity) {
        this.name = name;
        this.capacity = capacity;
    }
}
```

This models real-world passenger bogies with:

* Name
* Seating capacity

---

### **4. Initialize Bogie List**

Create a dynamic list to store bogie objects:

```
List<Bogie> bogies = new ArrayList<>();
```

---

### **5. Add Passenger Bogies**

Insert bogies with capacities:

```
bogies.add(new Bogie("Sleeper", 72));
bogies.add(new Bogie("AC Chair", 60));
bogies.add(new Bogie("First Class", 40));
```

---

### **6. Display Before Sorting**

```
Before Sorting:
Sleeper -> 72
AC Chair -> 60
First Class -> 40
```

---

### **7. Apply Comparator for Sorting**

Use `Comparator.comparingInt()` with a lambda expression:

```
bogies.sort(Comparator.comparingInt(b -> b.capacity));
```

* Sorts bogies in **ascending order**
* Uses **lambda expression** for concise logic

---

### **8. Display After Sorting**

```
After Sorting (by capacity):
First Class -> 40
AC Chair -> 60
Sleeper -> 72
```

---

### **9. Completion Message**

```
UC7 operations completed successfully...
```

---

## **Actor & Flow**

**Actor:** User

**Flow:**

1. User creates passenger bogie objects
2. Bogies are stored in a list
3. System applies Comparator logic
4. Bogies are sorted by capacity
5. Sorted list is displayed
6. Program continues

---

## **Key Concepts Used in UC7**

* **Comparator Interface** – Defines custom sorting logic
* **Custom Objects (Bogie)** – Represents real-world data
* **List Collection** – Stores objects dynamically
* **sort() Method** – Applies sorting logic
* **Lambda Expressions** – Simplifies comparator implementation
* **Separation of Data and Logic** – Improves code clarity

---

## **Key Requirements**

* Create a `Bogie` class with name and capacity
* Create a `List<Bogie>`
* Add bogies: Sleeper, AC Chair, First Class
* Use `Comparator.comparingInt()`
* Sort and display bogies

---

## **Key Benefits**

* Introduces **object-based data handling**
* Demonstrates **custom business logic in sorting**
* Improves **train planning and capacity analysis**
* Promotes **clean and maintainable code design**
* Prepares for **advanced collection processing in real-world systems**

---

## **Outcome of UC7**

After completing this procedure:

* Passenger bogies are sorted based on **capacity**
* The system uses **custom comparison logic effectively**
* Code structure reflects **real-world modeling and separation of concerns**
* The application demonstrates **advanced use of collections and Comparator**

---

