![277147603-6e6d123c-60ae-4f9c-a27c-c4fc7e57d57c](https://github.com/sithihajara/19AI405FUNDAMENTALSOFARTIFICIALINTELLIGENCE/assets/94219582/2f35ae7d-dcf9-4c39-8a7b-a9c54c163dd3)# 19AI405 FUNDAMENTALS OF ARTIFICIALINTELLIGENCE 
# Laboratory Experiments
## ExpNo 1 : Implement Depth First Search Traversal of a Graph
### Name: Saravanan N
### Register Number/Staff Id: TSML006
### Aim:
To Implement Depth First Search Traversal of a Graph using Python 3.

#### Theory:
Depth First Traversal (or DFS) for a graph is like Depth First Traversal of a tree. The only catch here is that, unlike trees, graphs may contain cycles (a node may be visited twice). Use a Boolean visited array to avoid processing a node more than once. A graph can have more than one DFS traversal. Depth-first search is an algorithm for traversing or searching trees or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking. Step 1: Initially, stack and visited arrays are empty.
![277147664-640b3c6f-3ac1-49a2-a955-68da9a71f446](https://github.com/sithihajara/19AI405FUNDAMENTALSOFARTIFICIALINTELLIGENCE/assets/94219582/61b9ddad-730a-4d09-996f-59ab7c5f015b)
Queue and visited arrays are empty initially. Stack and visited arrays are empty initially. Step 2: Visit 0 and put its adjacent nodes which are not visited yet into the stack

![277147583-86dcf7d9-1f9d-49b0-a821-5976a6e77606](https://github.com/sithihajara/19AI405FUNDAMENTALSOFARTIFICIALINTELLIGENCE/assets/94219582/0fe8be50-f0c2-4edf-9c7c-6a12b1a84009)
Visit node 0 and put its adjacent nodes (1, 2, 3) into the stack Visit node 0 and put its adjacent nodes (1, 2, 3) into the stack

Step 3: Now, Node 1 at the top of the stack, so visit node 1 and pop it from the stack and put all of its adjacent nodes which are not visited in the stack
![277147597-e6017942-08b1-4742-87ad-c97eb97bf985](https://github.com/sithihajara/19AI405FUNDAMENTALSOFARTIFICIALINTELLIGENCE/assets/94219582/163fe4c3-cb75-4212-97c2-938934b4dd7a)

Visit node 1 Visit node 1

Step 4: Now, Node 2 at the top of the stack, so visit node 2 and pop it from the stack and put all of its adjacent nodes which are not visited (i.e,3, 4) in the stack.
![image](https://github.com/sithihajara/19AI405FUNDAMENTALSOFARTIFICIALINTELLIGENCE/assets/94219582/431364a3-724a-4ed2-952d-f415e10b0b42)

Visit node 2 and put its unvisited adjacent nodes (3, 4) into the stack Visit node 2 and put its unvisited adjacent nodes (3, 4) into the stack

Step 5: Now, Node 4 at the top of the stack, so visit node 4 and pop it from the stack and put all of its adjacent nodes which are not visited in the stack. 

![277147620-20b76a05-5668-4da5-8189-e10fb1bb7238](https://github.com/sithihajara/19AI405FUNDAMENTALSOFARTIFICIALINTELLIGENCE/assets/94219582/dc4f6ce3-0bd1-44f3-9034-be9f241b888a)
Visit node 4 Visit node 4

Step 6: Now, Node 3 at the top of the stack, so visit node 3 and pop it from the stack and put all of its adjacent nodes which are not visited in the stack
![277147623-3b88f04a-7846-4f75-89b4-22bbd5b48e52](https://github.com/sithihajara/19AI405FUNDAMENTALSOFARTIFICIALINTELLIGENCE/assets/94219582/9139080d-6514-47d6-a7dd-ffd84ba1d69b)
Visit node 3 Visit node 3

Now, the Stack becomes empty, which means we have visited all the nodes, and our DFS traversal ends.











