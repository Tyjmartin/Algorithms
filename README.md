# Algorithms
This class was designed to teach the everyday algorithms a programmer might use in every day problems. 


# Assignment 1
This project was about learning to take advantage of lists and how creative someone can get with them. The idea was to
create a LISP interpreter in Java. LISP is a symbolic processing language so we were able to use the brackets to help
with breaking down the problem. 

It is done by creating a list of lists as LISP can have infinite number of lists, so I created a node that has a right
and a down to represent the build of my list. Then I created a stringtokenizer to read in the list and apply spaces where
spaces should be added. The LISP class is where I handled all my details of actually breaking down the list for output
the only thing I was missing from then was a copy function.


# Assignment 2
This was dealing with Binary Search Trees and Threads, which takes in a list of names and outputs the number of letters for
each letter in the name. For example my name Tyler Martin would be r-2, t-2, a-1,e-1,i-1,l-1,m-1,n-1,y-1. It does the letters
in order because it is a BST and it does a new thread for each new branch in the BST. 

The main part of this project is in the BST file as that is the breakdown of the tree and threading it is done both ways for
printing and testing purposes. This is all done with the help of lists and my node class has 2 different nodes it can use. It
uses the main node for the calls in main then it uses character node to break down the names. The main class deals with
inputting the data and reading the list of names.

# Assignment 3
In this project we were tasked with using Prim's algorithm which is a variation of Dijkstra's algorithm and we use it to 
help find the mininimum spanning tree of user created graph. The output is the edge weight of the Euclidean distance
between any two vertices in a space of 580x580. We needed to the graph be bi-directional, so each edge could be listed twice.
It had to calculate the space inbetween the coordinate space and those vertices. The final print out shows the total edge 
weight and the Minimum Spanning tree

This takes advantage of interfaces as I have a main Heap and Keyednode and from that minHeap uses Heap and edge uses KeyedNode.
MinHeap is used to create all the data needed to carry out the project. It is using generics to help with this and generics
were not something I was too familiar with at this time so it took a lot of time to get this to work. The table class is 
used to get locations and do the math for the map. The testharnessA is where all of the work is done including the print out
for the data. It was hard coded and can be changed in the program by changing the verNum and MinHeap<Edge>.

# Assignment 4
This was the hardest assignment I have done yet in my degree and it wasn't that it was overly difficult just trying
to get the testing to work and then time constraints made it difficult. The idea was to do LZW compression which is similar
to winrar and winzip but a bit different. We were also supposed to implemet a hash table with external chaining to hold
the code table. The hash table was to determine the prefix and if it does not exist we needed to create it. The problem was
with the hashtable and the external chaining as this concept at the time was very far out. I was only able to complete the
compression part and not the decompression.
