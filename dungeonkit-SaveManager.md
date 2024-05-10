# SaveManager `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.SaveManager[[SaveManager]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> DungeonKIT.SaveManager
```

## Members
### Methods
#### Public Static methods
| Returns | Name |
| --- | --- |
| `void` | [`Load`](#load)() |
| `void` | [`Save`](#save)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### SaveManager
```csharp
public SaveManager()
```

### Methods
#### Save
```csharp
public static void Save()
```

#### Load
```csharp
public static void Load()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
