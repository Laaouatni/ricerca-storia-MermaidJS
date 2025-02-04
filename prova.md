```mermaid
flowchart TB
  0[...]
  1[NASCITA U.R.S.S]
  subgraph 15[" "]
    subgraph 10[" "]
      100[U]
      1000[...]
      100 --> 1000
    end
    subgraph 11[" "]
      110[R]
      1100[...]
      110 --> 1100
    end
    subgraph 12[" "]
      120[S]
      1200[...]
      120 --> 1200
    end
    subgraph 13[" "]
      130[S]
      1300[...]
      130 --> 1300
    end
  end
  0 --> 1 --> 100 & 110 & 120 & 130
```