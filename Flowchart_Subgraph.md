::: mermaid

flowchart
subgraph one [Single]
A1
end

subgraph two [Double]
direction LR
B1 --> B2
end

subgraph three [Triple]
direction TB
C1 --> C2 & C3
end

one --> two --> three

subgraph Anotherone [Single1]
AA1
end

subgraph MyGroupedMultiple
direction TB

    subgraph Anothertwo [Double1]
    direction LR
    BB1 --> BB2
    end

    subgraph Anotherthree [Triple1]
    direction LR
    CC1 --> CC2 & CC3
    end

end
Anotherone --> MyGroupedMultiple
Anothertwo --> Anotherthree
