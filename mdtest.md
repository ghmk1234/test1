```mermaid
flowchart TB
    aNode
    bNode
    cNode
    dNode
    eNode
    fNode[cNode]
    aNode --> bNode --> cNode --> dNode
    aNode <--> eNode <--> fNode <--> dNode
```
