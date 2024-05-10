# Colorblind `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph Wilberforce
  Wilberforce.Colorblind[[Colorblind]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> Wilberforce.Colorblind
```

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### Colorblind
```csharp
public Colorblind()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
