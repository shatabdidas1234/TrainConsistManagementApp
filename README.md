## **Project Procedure – UC6: Map Bogie to Capacity (HashMap)**

### **1. Continue the Project**

Using the existing Java project and class **TrainConsistManagementApp.java**, extend the system to associate each bogie with its **seating or load capacity**.

---

### **2. Display UC6 Title**

Inside the `main` method, print:

```
==================================
UC6 - Map Bogie to Capacity (HashMap)
```

(Note: Order may vary since HashMap is unordered.)

---

### **8. Completion Message**

```
UC6 bogie-capacity mapping completed...
```

---

## **Actor & Flow**

**Actor:** User

**Flow:**

1. User creates bogie-capacity mapping
2. System stores data in `HashMap`
3. Key–value pairs are inserted using `put()`
4. System iterates using `entrySet()`
5. Bogie capacities are displayed
6. Program continues

---

## **Key Concepts Used in UC6**

* **Map Interface** – Stores key–value relationships
* **HashMap Class** – Efficient key-based storage using hashing
* **put() Method** – Inserts mappings
* **Key–Value Association** – Links bogie to its capacity
* **entrySet() Iteration** – Access both key and value together
* **Fast Lookup** – Retrieve capacity using bogie name
1. User adds bogie names
2. System inserts them into `LinkedHashSet`
3. Duplicate entries are ignored
4. Insertion order is preserved
5. Final formation is displayed

---

## **Key Concepts Used in UC5**

* **Set Interface** – Ensures no duplicate elements
* **LinkedHashSet Class** – Maintains insertion order
* **add() Method** – Inserts elements
* **Automatic Deduplication** – No manual validation required
* **Order Preservation** – Maintains sequence of insertion

---

## **Key Requirements**

* Create a `HashMap<String, Integer>`
* Insert bogie capacities (Sleeper, AC Chair, First Class, Cargo)
* Use `put()` for mapping
* Iterate using `entrySet()`
* Display bogie and capacity
* Create a `LinkedHashSet<String>` for train formation
* Add bogies: Engine, Sleeper, Cargo, Guard
* Add duplicate value intentionally
* Print final formation
* Verify:

  * No duplicates
  * Order is preserved

---

## **Key Benefits**

* Models **real-world attribute mapping**
* Introduces **key–value data structures**
* Enables **fast lookup and validation**
* Builds foundation for **data-driven applications**
* Prepares for **advanced analytics and planning systems**

---

## **Outcome of UC6**

After completing this procedure:

* Each bogie is successfully mapped to its **capacity**
* Data is stored in an efficient **key–value structure**
* The system supports **quick retrieval of bogie details**
* The application demonstrates effective use of **HashMap for real-world data modeling**

---




* Combines **uniqueness + order preservation**
* Prevents **duplicate bogie entries**
* Maintains **realistic train sequence**
* Demonstrates when to use **LinkedHashSet over HashSet and List**

---

## **Outcome of UC5**

After completing this procedure:

* Train formation maintains **unique bogies only**
* Original insertion sequence is **retained**
* Duplicate entries are **automatically eliminated**
* The application demonstrates effective use of **LinkedHashSet for ordered and unique data management**

---

