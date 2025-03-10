```mermaid
graph TD;
    CEO["CEO"]
    COO

    CEO --> COO

    subgraph EngExCo
        direction TB
        VP_Eng["Slava"]
        CTO["Stephan"]
        Dir_Eng["Hyejin"]
    end

    CEO --> EngExCo
    EngExCo --> EngKR
    EngExCo --> EngNonKR
    
    subgraph EngKR
    end
    subgraph EngNonKR
    end

    %%DD[Director of Design]
    %%ADD["Assc Dir Design"]
    %%DD --> ADD

```
