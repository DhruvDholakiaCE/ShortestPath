# ShortestPath
Find shortest path from one vertex to another in an undirected graph.

## Inputs and Outputs

#### Inputs/Output Specifications:
- one kind of input is the specification of a set of vertices V, and set of edges E of the undirected graph. The specification of a set of vertices starts with ‘V’, followed by a space, followed by an integer greater than one, all in one single line. If the integer that follows the V is i, then we assume that the vertices are identified by 1, . . . , i. The specification for a set of edges starts with ‘E’. It then has a space, followed by the set of  edges in a single line delimited by ‘{’ and ‘}’. The two vertices of an edge are delimited by ‘<’ and ‘>’ and separated by a comma. The edges in the set are also separated by a comma. There are no whitespace characters within the { }.

- The only other kind of input starts with an ‘s’. It asks for a shortest path from the first vertex to the second that is specified after the s. The s is followed by a space, a vertex ID, another space, and a second vertex ID. The lines 2-8-10 and 5-2-3-1 above are outputs of the s commands that 1 immediately precede them. The output comprises vertex IDs separated by -, with no whitespace within. If a path does not exist between the vertices, you should output an error

#### Example:

$ ./ece650-a2  
V 15  
E {<2,6>,<2,8>,<2,5>,<6,5>,<5,8>,<6,10>,<10,8>}     
s 2 10 
2-8-10  
V 5  
E {<1,3>,<3,2>,<3,4>,<4,5>,<5,2>}  
s 5 1  
5-2-3-1  

## Authors

- [@DhruvDholakia](https://www.github.com/DhruvDholakiaCE)

