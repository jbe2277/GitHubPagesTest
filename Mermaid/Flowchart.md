```mermaid
flowchart TB

  subgraph P["Presentation"]
    direction LR
    P_C["Converters"]
    P_S["Services"]
    P_V["Views"]
  end

  subgraph A["Applications"]
    direction LR
    A_C["Controllers"]
    A_S["Services"]
    A_VM["ViewModels"]
    A_V["Views"]
  end

  D["Domain"]

  P --> A
  A --> D
  A_C --> A_S
  A_C --> A_VM
  A_VM --> A_S
  A_VM --> A_V
```
