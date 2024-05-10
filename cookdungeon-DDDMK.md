# DDDMK `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.DDDMK[[DDDMK]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.DDDMK
```

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### DDDMK
```csharp
public DDDMK()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
