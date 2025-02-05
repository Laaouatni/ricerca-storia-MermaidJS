```mermaid
flowchart LR
  0[CON I BOLSCEVISCHI]
  subgraph 3[" "]
    1[PRIMA]
    10[SPERANZE <br> DEMOCRAZIA <br> OPERAIA]
    1 --> 10
  end
  2[DOPO]
  0 --> 1 & 2
  subgraph 4[" "]
    40[DITTATURA PROLETARIATO]
    400[MONOPOLIO POTERE]
    40 <--> 400
  end
  2 --> 4
  41((MA))
  10 --> 41 --> 4
```