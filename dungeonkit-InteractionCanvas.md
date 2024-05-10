# InteractionCanvas `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.InteractionCanvas[[InteractionCanvas]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> DungeonKIT.InteractionCanvas
```

## Members
### Properties
#### Public  properties
| Type | Name | Methods |
| --- | --- | --- |
| `string` | [`interaction`](#interaction) | `get` |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### InteractionCanvas
```csharp
public InteractionCanvas()
```

### Properties
#### interaction
```csharp
public string interaction { get; }
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
