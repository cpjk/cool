# Data Structures

## Priority queues
- More flexible  than simple sorting, since new items can be added at arbitrary intervals.
### Basic operations
- Insert
- Find-min/max
- Delete min/max

#### Faster heap construction
1. Copy all of the input elements into the underlying array.
2. Start from the leaves and repeatedly bubble down improperly ordered parent nodes.
- O(n) w.r.t the numberof elements, since the maximum number of swaps in the bubble down ends up being low for most of the elements.


note: in a full binary tree on n nodes, there are ceil(n/2) leaves.

## Disjoint Sets
### Basic Operations
- Find: return the set the given element is part of
- Union: join two disjoint sets into a single set
### Union-find
#### basic operations
