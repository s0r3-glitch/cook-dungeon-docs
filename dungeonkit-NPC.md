# NPC `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.NPC[[NPC]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> DungeonKIT.NPC
```

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### NPC
```csharp
public NPC()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
