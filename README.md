# Java-util-collections

This repository provides a detailed and visual representation of the **Java Collection Framework**, including its core interfaces, classes, cursors, and their hierarchical relationships.

## 📚 Overview

The content covers:
- Java Collections hierarchy (`Collection`, `List`, `Set`, `Queue`, `Map`, etc.)
- Iterable and Iterator interface relationships
- Java Cursor types: `Enumeration`, `Iterator`, `ListIterator`
- Class-to-interface-to-method flow (as per `Iterable` and `iterator()`)

## 🧭 Visual Diagram

A clean and comprehensive visual diagram showing:

- Full class and interface hierarchy
- Cursor types with Java version
- Iterator method flow (from class to methods like `hasNext()`, `next()`)

![Java Collection Framework Diagram](A_diagram_depicts_the_class_and_interface_hierarch.png)

## 📁 Folder Structure


```

src/
└── java/
    ├── lang/
    │   └── Object.java                      # Root superclass
    │
    └── util/
        ├── interfaces/
        │   ├── Iterable.java               # Java 1.5
        │   ├── Collection.java             # Java 1.2
        │   ├── List.java
        │   ├── Set.java
        │   ├── SortedSet.java
        │   ├── NavigableSet.java
        │   ├── Queue.java
        │   ├── Deque.java
        │   ├── Map.java
        │   ├── SortedMap.java
        │   ├── NavigableMap.java
        │   ├── Iterator.java               # Java 1.2
        │   ├── ListIterator.java           # Java 1.2
        │   ├── Enumeration.java            # Legacy
        │   ├── Comparable.java
        │   └── Comparator.java
        │
        ├── classes/
        │   ├── ArrayList.java
        │   ├── LinkedList.java
        │   ├── Vector.java
        │   ├── Stack.java
        │   ├── HashSet.java
        │   ├── LinkedHashSet.java
        │   ├── TreeSet.java
        │   ├── PriorityQueue.java
        │   ├── ArrayDeque.java
        │   ├── HashMap.java
        │   ├── LinkedHashMap.java
        │   ├── TreeMap.java
        │   ├── Hashtable.java
        │   ├── Properties.java
        │   ├── WeakHashMap.java
        │   ├── IdentityHashMap.java
        │   └── EnumMap.java
        │
        └── utils/
            ├── Collections.java
            ├── Arrays.java
            └── Objects.java


```
