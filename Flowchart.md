::: mermaid

flowchart
A[A: Family Tree]
B[B: Husband]
C[Wife]
E[Child]

A --> B
A --> C
B --> E
C --> E
A --> D
D --> |No|F
F <--> G
G -.-> H
H ==> |Decide|I[Hello]
%%Extend/stretch the block to next level as below
A --> J
A ---> K
A ----> L
A -.-> M
A -..-> N
A -...-> O
A ==> P
A ===> Q
A ====> R
