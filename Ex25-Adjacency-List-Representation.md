# Ex 5E Adjacency List Representation
## DATE: 30.04.25
## AIM:
To write a C program to represent the given graph using the adjacency list.

## Algorithm
1. Read the number of vertices and number of edges.
2.	Read all edge pairs (source and destination) and store them.
3.	Create a graph using the input edge list.
4.	Print the adjacency list representation of the graph.

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: Nikshitha G
RegisterNumber: 212223110031 
*/
int main(void)
{ int n,i; scanf("%d",&N);
scanf("%d",&n);
// input array containing edges of the graph (as per the above diagram)
// (x, y) pair in the arrayrepresents an edge fromx to y struct Edge edges[n];
for (i = 0; i < n; i++)
{
// get the source and destination vertex scanf("%d",&edges[i].src);
scanf("%d",&edges[i].dest);

}

// construct a graph from the given edges struct Graph*graph= createGraph(edges, n);
// Function to print adjacency list representation of a graph printGraph(graph);
return 0;
}

```

## Output:

![image](https://github.com/user-attachments/assets/95d6adf8-3849-4a48-a10e-9331bcc657c6)

## Result:
Thus, the C program to represent the given graph using the adjacency list is implemented successfully
