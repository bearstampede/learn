# Data Structures

## Intro

## Linked Lists
### Singularly Linked Lists
#### Invariants 
1. An DList's size variable is always correct.
2. There is always a tail node whose next reference is null.

#### Code Example (Java)
```Java
public class ListNode {
  public int item;
  public ListNode next;
} 
public ListNode(int i, ListNode n) {
  item = i;
  next = n;
}
public ListNode(int i) {
  this(i, null);
}
```

```Java
public class SList {
  private SListNode head;             // First node in list.
  private int size;                   // Number of items in list.

  public SList() {                    // Here's how to represent an empty list.
    head = null;
    size = 0;
  }

  public void insertFront(Object item) {
    head = new SListNode(item, head);
    size++;
  }
}
    
```
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times
- Insertion: O(1) 
- Deletion: O(1)
- Indexing: O(n)
- Searching: O(n)



### Doubly Linked Lists
#### Invariants 
#### Code Example (Java)
#### Visual Example

#### Run Times
- Insertion: O(1) 
- Deletion: O(1)
- Indexing: O(n)
- Searching: O(n)

### Hash Tables
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times

### Stacks
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times

### Queues
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times

## Trees
### Binary Trees
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times

### 2-3-4 Trees
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times

### Red Black Trees
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times

### Splay Trees
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times

### Traversals
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times


## Heaps

## Graphs
### Undirected Graphs
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times

### Directed Graphs
#### Invariants 
#### Code Example (Java)
#### Visual Example
#### Run Times

### Breadth First Search
### Depth First Search


## Disjoint Sets

## Resources
## Colophon
