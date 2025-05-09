# Linked-lists

README 
  Singly Linked List
A Singly Linked List is a linear data structure where each node contains:

Data — The value stored in the node.

Next — A reference to the next node in the sequence.

Features:
Insertion at the Beginning: O(1) — Performed in constant time since only the head pointer is updated.

Insertion at the End: O(n) — Traverses the list to find the last node before inserting.

Deletion: O(n) — Searches for the node, then bypasses it to remove it from the sequence.

Dynamic Resizing: Nodes are created and deleted dynamically.

Memory Efficient: Only the required nodes are stored, with no pre-allocation.

  Doubly Linked List
A Doubly Linked List extends the functionality of a Singly Linked List by adding:

Prev — A reference to the previous node, allowing traversal in both directions.

Features:
Insertion at the Beginning: O(1) — Constant time, only the head is updated.

Insertion at the End: O(n) — Traverses the list to find the last node.

Deletion: O(n) — Removes the node and updates pointers of both neighbors.

Backward Traversal: Allows navigation from the tail to the head.

Memory Efficient: Only active nodes are maintained in memory.

  Circular Linked List
A Circular Linked List is a variant of a Singly Linked List where:

The last node points back to the first node.

The list can be traversed starting from any node.

Features:
Insertion at the Beginning: O(1) — New node is added and linked back to the head efficiently.

Insertion at the End: O(n) — Traverses to the last node and updates its next pointer to the new node.

Deletion: O(n) — Finds the node and re-links pointers to exclude it.

Circular Traversal: The list can be continuously traversed due to its circular nature.

Memory Efficient: Only active nodes are linked.
