# Door `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.Door[[Door]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> DungeonKIT.Door
```

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### Door
```csharp
public Door()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
