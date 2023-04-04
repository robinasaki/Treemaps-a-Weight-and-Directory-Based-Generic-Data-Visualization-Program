# Treemaps: a Weight-and-Directory Based Genertic Data Visualization Program
### Chenxu Robin Mao, Abdul Mubarak
Winter 2023, a project of CSC148 at University of Toronto.

-----------

## About

**Treemap** is a common visualization technique that shows the data weight and its directory. 

This program focuses on layering data nodes and returns an aggregate dynamic visualization for users. 

It contains the following three modes,

- **TMTree Mode**: visualizing simple data trees.

- **FileTree Mode, DirectoryTree Mode**: convert operating system data (and directories) into nodes and visualize.

- **ChessTree Mode**: convert chess moves into data trees and visualize.

## Controls

- `e`: expand: expand the directory to its sub-level content.
    
- `a`: expand all: expand all directories to the smallest unit.
    
- `c`: collapse: collapse the directory to the pre-level content.
    
- `x`: collapse all: collapse all directories to a single root node.
    
- `m` while hovering over a node is another node selected: move: move the node into the subtree of the target node.
    
- `arrow up` and `arrow down`: change data size: each `arrow up` increases the data size by 1% and each `arrow down` decreases the data size by 1%.


## Other Treemap Applications

> Disk Inventory X: http://www.derlien.com

> WinDirStat: https://portableapps.com/apps/utilities/windirstat_portable

> KDirStat: https://kdirstat.sourceforge.net
