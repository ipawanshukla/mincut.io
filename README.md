 # Mincut Max Flow Graph Simulation
<br>
 ## Aim:- Program to simulate the graph using Mincut Max Flow Simulation ## <br><br>
<br>
###### Technologies Used:-  <br>
<br>
JavaScript libraries <br>
jQuery3.2.1 <br>
jQuery UI1.12.1 <br>
Hammer.js2.0.7 <br>
<br>
 ###### UI Framework USED:-  <br>
Boot Strap 4.0 <br>
<br>
 ###### Programming Language Used:-  <br>
JavaScript <br>
<br>
###### Data Structures Used:- <br>
Array <br>
JSON <br>
<br>
###### Algorithms used:- <br>
Graph Traversal (DFS) <br>
Flow(Min Cut Max Flow)<br>
<br>
###### Program Flow:-  <br>
Consider the directed graph as default in the program. <br>
Vertices :- S,A,B,C,D,T <br>
Default Source:- S <br>
Default Destination:- T <br>
Edges:- <br>
  S->A <br>
  S->C <br>
  A->B <br>
  A->D <br>
  D->T <br>
  B->T <br>
  C->B <br>
<br>
Path Obtained and their Max flow:-  <br>
  s->a->b->t (10) <br>
  s->a->d->t (20) <br>
  s->c->b->t (15) <br>
 <br>
###### Direction For Use:- <br>
  1. Suppose we want to insert the path s,a,b,t . We can do this in two ways:- <br>
    a) Step By Step Insertion <br>
    b) Direct Insertion <br>
    a) Step By Step Insertion :- <br>
        For this we will have to insert the path in the top left text box . Vertices sepersted by "," . <br>
        The Path given should follow the edge order like <br>
        s->a->b->t. If given s,b,a,t then the path will not be simulated. <br>
        Afterwards we can see the flow from one vertex to another using the next button in the top middle. <br>
    b)  Direct Insertion:- <br>
        Once  the graph is loaded ; if there exits a path then the path will automatically reflect in the path section .  <br>
        We can directly click on the left button(with down arrow symbol ) followed by the path vertices to insert the path and get the flow.
  2. Now if we want to change the source and destination we can update the source and destination vertices also . Using the text box provided. <br>
      But these source and destination should have a valid path or else the flow path will not be generated as well as the flow. <br>
  3. If we want to alter the graph we can make use of the edit graph tool to do so.<br>
        
  

