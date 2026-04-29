```mermaid
block
columns 1
  block:P["Presentation"]
    P_C["Converters"]
    P_S["Services"]
    P_V["Views"]
  end
  space
  block:A["Applications"]
    A_C["Controllers"]
    A_S["Services"]
    A_VM["ViewModels"]
    A_V["Views"]
  end
  space
  D["Domain"]
  P --> A
  A --> D
```
