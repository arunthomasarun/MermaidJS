::: mermaid

%%{
init:{
'flowchart':{
'curve': 'linear'
}
}
}%%

flowchart TB

A([Start]) --> B[/Input X/]
B --> C{Is X > 5}
C --x |Yes|D((stop))
C --> |No|F[/Print X/]
F --> G[X = X+1]
G --> C
