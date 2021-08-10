# Linked List

Linked List is a sequence of Nodes that are connected/linked to each other.

There are two types of linked list (singly and doubly)

Singly means that the nodes inside the list have one reference while the double will have two references.

The node is the link or the stack stored in the linked list, it will have the data/values for the link.

Next is a proberty for the node which means it is the reference for the next node.

Head is the first node in the linked list.

A singly linked list will look like this
![Single LL](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/images/LinkedList1.PNG)

one of the most thing to know in linkedlist is that we can't use the for and the foreach loop but we can use while loop to check for the next node if it is null or not.

## Adding Node

To add a node we have to check every node in the list weather it has data or not.

If we want to replace the head we have to assure the reference will be the same pointing to the next node to not lose the list
then we add using the method add().

ALGORITHM Add(newValue)

// INPUT <-- Value to add

// OUTPUT <-- No output

  newNode <-- NEW Node

  newNode.Value <-- newValue

  newNode.Next <-- Head

  Head <-- newNode
