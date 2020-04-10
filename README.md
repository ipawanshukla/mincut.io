#Mincut Max Flow Graph Simulation

Aim:- Program to simulate the graph using Mincut Max Flow Simulation

Technologies Used:- 

JavaScript libraries
jQuery3.2.1
jQuery UI1.12.1
Hammer.js2.0.7

UI Framework USED:- 
Boot Strap 4.0

Programming Language Used:- 
JavaScript

Data Structures Used:-
Array
JSON

Algorithms used:-
Graph Traversal (DFS)
Flow(Min Cut Max Flow)

Program Flow:- 
Consider the directed graph as default in the program.
Vertices :- S,A,B,C,D,T
Default Source:- S
Default Destination:- T
Edges:- 
  S->A
  S->C
  A->B
  A->D
  D->T
  B->T
  C->B

Path Obtained and their Max flow:- 
  s->a->b->t (10)
  s->a->d->t (20)
  s->c->b->t (15)
 
Direction For Use:- 
  1. Suppose we want to insert the path s,a,b,t . We can do this in two ways:-
    a) Step By Step Insertion
    b) Direct Insertion
    a) Step By Step Insertion :-
        For this we will have to insert the path in the top left text box . Vertices sepersted by "," . The Path given should follow the edge order like 
        s->a->b->t. If given s,b,a,t then the path will not be simulated.
        Afterwards we can see the flow from one vertex to another using the next button in the top middle.
    b)  Direct Insertion:-
        Once  the graph is loaded ; if there exits a path then the path will automatically reflect in the path section . 
        We can directly click on the left button(with down arrow symbol ) followed by the path vertices to insert the path and get the flow.
  2. Now if we want to change the source and destination we can update the source and destination vertices also . Using the text box provided.
      But these source and destination should have a valid path or else the flow path will not be generated as well as the flow.
  3. If we want to alter the graph we can make use of the edit graph tool to do so.
        
  

