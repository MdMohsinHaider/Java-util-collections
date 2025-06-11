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


``
java.lang
└── Object (root of all classes)

java.util
├── Iterable<E>              // Java 1.5 — super interface for Collection
│   └── Collection<E>        // Java 1.2
│       ├── List<E>
│       │   ├── ArrayList<E>
│       │   ├── LinkedList<E>
│       │   ├── Vector<E>
│       │   │   └── Stack<E>
│       ├── Set<E>
│       │   ├── HashSet<E>
│       │   ├── LinkedHashSet<E>
│       │   └── SortedSet<E> / NavigableSet<E>
│       │       └── TreeSet<E>
│       └── Queue<E>
│           ├── PriorityQueue<E>
│           ├── ArrayDeque<E>
│           └── Deque<E>
│               ├── LinkedList<E>
│               └── ArrayDeque<E>
│
├── Map<K,V>
│   ├── HashMap<K,V>
│   │   └── LinkedHashMap<K,V>
│   ├── TreeMap<K,V>
│   ├── Hashtable<K,V>
│   │   └── Properties
│   ├── WeakHashMap<K,V>
│   ├── IdentityHashMap<K,V>
│   └── EnumMap<K,V>
│
├── SortedMap<K,V> / NavigableMap<K,V>

├── Comparator<T>            // For sorting
├── Comparable<T>            // For natural order sorting
│
├── Cursors                  // Conceptual (not an actual package)
│   ├── Enumeration<E>       // Java 1.0 — Legacy cursor
│   ├── Iterator<E>          // Java 1.2 — Modern cursor from Iterable
│   └── ListIterator<E>      // Java 1.2 — Enhanced Iterator for List

├── Utility Classes
│   ├── Collections
│   ├── Arrays
│   └── Objects


``
