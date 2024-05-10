# TRL `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.TRL[[TRL]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.TRL
```

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### TRL
```csharp
public TRL()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
