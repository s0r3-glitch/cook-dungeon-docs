# UPLEVEL `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.UPLEVEL[[UPLEVEL]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.UPLEVEL
```

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### UPLEVEL
```csharp
public UPLEVEL()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
