# An Implementations on a Binary Tree and Shortest Transformation Sequence

This repository contains three Python implementations for solving different problems related to binary trees. 
Each implementation adheres to specific constraints and uses efficient algorithms to achieve the desired results.

### 1. Maximum Width of a Binary Tree

#### Description
Calculates the maximum width of a binary tree. The width is defined as the number of nodes between the leftmost and rightmost non-null nodes in any level, including null nodes.

#### Constraints
- Number of nodes: \(1 \leq \text{nodes} \leq 3000\)
- Node values: \(-100 \leq \text{value} \leq 100\)

#### Usage
- Function: `widthOfBinaryTree(root: TreeNode) -> int`
- Input: Binary tree root node.
- Output: Integer representing the maximum width.

#### Example
Input tree:
```
        1
       / \
      3   2
     / \    \
    5   3    9
```

Output:
```
Maximum Width: 4
```

---

### 2. Maximum Path Sum in a Binary Tree

#### Description
Finds the maximum path sum in a binary tree, where a path is any sequence of nodes connected by edges (not necessarily passing through the root). 

#### Constraints
- Number of nodes: \(1 \leq \text{nodes} \leq 30,000\)
- Node values: \(-1000 \leq \text{value} \leq 1000\)

#### Usage
- Function: `maxPathSum(root: TreeNode) -> int`
- Input: Binary tree root node.
- Output: Maximum path sum.

#### Example
Input tree:
```
        -10
       /    \
      9      20
           /   \
         15     7
```

Output:
```
Maximum Path Sum: 42 (Path: 15 -> 20 -> 7)
```


### 3. Shortest Transformation Sequence

#### Description
Finds the shortest transformation sequence from a `beginWord` to an `endWord`, where each transformation changes only one character at a time, and each transformed word must exist in a given word list.

#### Constraints
- Word list size: \(1 \leq \text{len(wordList)} \leq 5000\)
- Word length: All words are of the same length.
- Each word consists only of lowercase English letters.

#### Usage
- Function: `ladderLength(beginWord: str, endWord: str, wordList: List[str]) -> int`
- Input:
  - `beginWord`: Starting word.
  - `endWord`: Target word.
  - `wordList`: List of valid transformation words.
- Output: Length of the shortest transformation sequence, or 0 if no such sequence exists.

#### Example
Input:
```python
beginWord = "hit"
endWord = "cog"
wordList = ["hot", "dot", "dog", "lot", "log", "cog"]
```

Output:
```
Shortest Transformation Sequence Length: 5 (Sequence: "hit" -> "hot" -> "dot" -> "dog" -> "cog")
```

### Setup and Requirements

1. Python Version: The scripts require Python 3.6 or higher.
2. Dependencies: No additional libraries are needed (uses Python's standard library).


### How to Run
1. Clone this repository:
   ```
   git clone https://github.com/your-repo-name/binary-tree-implementations.git
   ```
2. Navigate to the project directory:
   ```
   cd binary-tree-implementations
   ```
3. Run any script or test the functions directly:
   ```python
   python your_script.py
