# TreeHelper

A python module for processing data structure for binary tree

## Getting Started

### Prerequisites

None


### Usage
The functions are class method, so you can call the functions directly. An instance is not necessary.
#### TreeGenerator.get_bin_tree()
Using a list of node values to get a binary tree.
The list is compliant with Leetcode binary tree format
```
tree1 = [1, 2, 3]
root1 = TreeGenerator.get_bin_tree(a)

tree2 = [1, 2, 3, None, 4, None, 5]
root2 = TreeGenerator.get_bin_tree(tree2)
```

#### TreeHelper.print_tree()
Following above examples, print the tree structure.

```
TreeHelper.print_tree(root1)
TreeHelper.print_tree(root2)
```
The output will like this:
```
total_layers:  2
      __1__
     /     \
    2       3
    
total_layers:  3
          ______1______
         /             \
        2__             3__
           \               \
            4               5

```

## License

This project is licensed under the MIT License
