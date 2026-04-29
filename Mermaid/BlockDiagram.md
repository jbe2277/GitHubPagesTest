```mermaid
block
columns 1
  block:Presentation
    Converters
    Services
    Views
  end
  space
  block:Applications
    Controllers
    Services
    ViewModels
    Views
  end
  space
  Domain
  Presentation --> Applications
  Applications --> Domain
```
