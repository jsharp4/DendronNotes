
list of nodes containing pointers to other nodes, or values. Ex:

```mermaid
graph TB;
subgraph Root
    direction TB
    R0
    R1
    R2=7
    R3
end
subgraph A
    direction TB
    A1
    A2=5
    A3
    end
subgraph B
    direction TB
    B1
    B2
    B3
end
R0-->A2=5
R1-->B2
B1-->R2=7
B3-->A2=5
A3-->A3

id((+))
R0-.->id((+))
R2=7-.->id((+))
id((+))-. 5+7 .->R3
```

Can perform operations:
* Make new node
* Read a node's value
* Set a node's field to a vlue
* set a node to arithmatic expressions of fields of the root node