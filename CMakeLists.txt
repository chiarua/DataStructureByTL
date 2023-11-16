cmake_minimum_required(VERSION 3.23)
project(DataStructureByTL)

set(CMAKE_CXX_STANDARD 14)

include_directories(Graph/cpp)

add_executable(DataStructureByTL
        Graph/C/AdjacencyListGraph.c
        Graph/C/AdjacencyMatrixGraph.c
        Graph/C/Dijkstra.c
        Graph/C/Floyd.c
        Graph/C/Kruskal.c
        Graph/C/Prim.c
        Graph/C/TopLogicalSort.c
        Graph/cpp/CycleDetection.h
        Graph/cpp/DenseGraph.h
        Graph/cpp/GraphReader.h
        Graph/cpp/main.cc
        Graph/cpp/PathSearcher.h
        Graph/cpp/ShortestPathSearcher.h
        Graph/cpp/SparseGraph.h
        LinearList/DoubleLinkList.c
        LinearList/LoopDoubleLinkList.c
        LinearList/LoopSingleLinkList.c
        LinearList/SingleLinkList.c
        Queue/CircularQueue.c
        Queue/Queue.c
        Search/BinarySearch.c
        Search/SequenceSearch.c
        Stack/Stack.c
        String/ForceMatch.c
        String/KMPMatch.c
        Tree/AVLBinaryTree.c
        Tree/BinarySearchTree.c
        Tree/BinaryTree.c
        Tree/BinaryTreeLevelTraverse.c
        Tree/BinaryTreeNonRecursivePost.c
        Tree/BinaryTreeNonRecursivePreAndIn.c
        Tree/BTree.c
        Tree/HuffmanTree.c
        Tree/InThreadBinaryTree.c
        Tree/PostThreadBinaryTree.c
        Tree/PreThreadBinaryTree.c)
