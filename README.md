Download Link: https://assignmentchef.com/product/solved-a-queue-class-is-given-as-follows
<br>
A queue class is given as follows, public class Queue{ Node front, rear; //front points to the beginning of the queue //rear points to the end of the queue class Node //inner class Node is the element of the queue { int value; Node next; private Node(int v) { value = v; next = null; } public boolean isEmpty(); //check whether the queue is empty public Node peek(); //return a node from the front public Node dequeue(); //remove a node from the front public void enqueue(Node item); //add a new node at the end public int size(); //return the number of nodes in the queue }