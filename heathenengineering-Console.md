# Console `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering
  HeathenEngineering.Console[[Console]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> HeathenEngineering.Console
```

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### Console
```csharp
public Console()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
