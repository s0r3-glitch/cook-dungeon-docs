# AICanvas `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.AICanvas[[AICanvas]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> DungeonKIT.AICanvas
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`UpdateUI`](#updateui)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### AICanvas
```csharp
public AICanvas()
```

### Methods
#### UpdateUI
```csharp
public void UpdateUI()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
