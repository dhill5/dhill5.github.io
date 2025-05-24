'''mermaid
flowchart TD
A([Start])--> B[Random Number Generated]
B --> C[User Input Required]
C --> D{Input Valid?}
D --> |NO| E[ERROR MESSAGE]
D --> |YES| F{Compare User Input to Generated Number}
F --> |TOO HIGH| G['TOO HIGH' DISPLAYED]
F --> |TOO LOW| H['TOO LOW' DISPLAYED]
F --> |CORRECT| I([END])
'''