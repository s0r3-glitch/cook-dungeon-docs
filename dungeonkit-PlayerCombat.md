# PlayerCombat `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.PlayerCombat[[PlayerCombat]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> DungeonKIT.PlayerCombat
```

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### PlayerCombat
```csharp
public PlayerCombat()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
