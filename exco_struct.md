```mermaid
graph TD;
    CEO["CEO"]
    COO

    CEO --> COO
    CEO --> CRO["CRO"]

    subgraph EngExCo
        direction TB
        VP_Eng["SO"]
        CTO["SJP"]
        Dir_Eng["YHJ"]
    end
    %% CRO -.- EngExCo

    CEO --> EngExCo
    EngExCo --> Eng-KR
    EngExCo --> Eng-ExKR

    %% This is all Korean-speaking engineers
    subgraph Eng-KR [Eng-KR:ar
Primary communication in Korean]
    end
    %% This is all engineers based outside of Korea
    subgraph Eng-ExKR [Eng-ExKR:
English communication]
    end


    %%DD[Director of Design]
    %%ADD["Assc Dir Design"]
    %%DD --> ADD

```
