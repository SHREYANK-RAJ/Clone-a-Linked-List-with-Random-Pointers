# Clone-a-Linked-List-with-Random-Pointers

This folder has solutions to the **"Clone a Linked List with Next and Random Pointer"** problem.  

It covers different approaches to deep copy a linked list where each node has:  
- `next` → points to the next node  
- `random` → points to any random node in the list (or `NULL`)  

## Files
- **Clone_a_linked_list_with_next_and_random_pointer_approach_1.cpp** → Uses a hashmap to store old-to-new node mapping.  
- **Clone_a_linked_list_with_next_and_random_pointer_approach_2.cpp** → Optimized method without extra space for hashmap.  
