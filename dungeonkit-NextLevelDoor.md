# NextLevelDoor `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.NextLevelDoor[[NextLevelDoor]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> DungeonKIT.NextLevelDoor
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`CheckLockStatus`](#checklockstatus)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### NextLevelDoor
```csharp
public NextLevelDoor()
```

### Methods
#### CheckLockStatus
```csharp
public void CheckLockStatus()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
