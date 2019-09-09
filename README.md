# Binary-Trees-Tries
presentation


Binary Trees and Tries

Octavio, James W, John


<img width="292" alt="Screen Shot 2019-09-06 at 9 59 47 AM" src="https://user-images.githubusercontent.com/49975993/64554869-0edfa580-d2f1-11e9-84d9-15be3ce75b9c.png">





In general, binary trees are used as an efficient means of representing hierarchical data, or as a way of storing data in a searchable format.
some real-world examples:
Database Indices- When you index a field, it is put in a binary tree for fast retrieval.
Sorting algorithms
Parsers
JPEG encoders use Huffman coding for compression,which requires a frequency sorted binary tree.



<img width="286" alt="Screen Shot 2019-09-06 at 10 19 04 AM" src="https://user-images.githubusercontent.com/49975993/64555065-6ed64c00-d2f1-11e9-9126-1cb3e42ef097.png">



Tries
https://medium.com/basecs/trying-to-understand-tries-3ec6bede0014
Created to solve the very problem of representing a set of words: a trie. 

The term “trie” comes from the word retrieval, and is usually pronounced “try”, to distinguish it from other “tree” structures.

A set of linked nodes, all connecting back to  an empty root node(empty string / “”).

Each node contains an array of pointers (child nodes), one for each possible alphabetic value.
The size of a trie is directly correlated to the size of all the possible values that the trie could represent.
A single node in a trie contains just two things:
A value, which might be null
An array of references to child nodes, all of which also might be null



Trees
https://medium.com/brandons-computer-science-notes/trees-the-data-structure-e3cb5aabfee9
A tree T = (V, E) consists of a set of vertices (V) and a set of edges (E).

The vertices are the “Nodes” in a tree and the edges are the “lines connecting them”.
Tree’s have exactly one path between two vertices. You cannot have more than one path between any 2 vertices.

A cycle is where you can “Move all the way around”. Acyclic means there is no cycle in the graph. If it is Acyclic it implies it is a tree.

A tree is often used to represent something that has a hierarchical structure, such as files and folders in a desktop.

Root, Parent, Child, Leaf

A binary tree has a degree of most 2. No vertex has a degree higher than 2. The two subtrees are called the left subtree and the right subtree. Makes comparisons by value.

Pre-Order : root, traverse left side subtree left, right, then right subtree left, then right.

In-Order : Traverse left subtree left, right, root., right subtree left, right

Post-Order : Traverse left subtree left, right, right subtree left, right, root.






Resources

Videos:
https://www.youtube.com/watch?v=TRg9DQFu0kU

https://www.youtube.com/watch?v=C3SsdUqasD4&list=PLA5Lqm4uh9Bbq-E0ZnqTIa8LRaL77ica6&index=2

Examples:
https://www.quora.com/What-are-the-real-world-examples-of-binary-trees-not-search-tree

https://study.com/academy/lesson/binary-trees-applications-implementation.html

Lecture notes on tries:
https://www.cs.cmu.edu/~fp/courses/15122-f10/lectures/18-tries.pdf
