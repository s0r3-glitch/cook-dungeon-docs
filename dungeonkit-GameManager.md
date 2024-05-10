# GameManager `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.GameManager[[GameManager]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> DungeonKIT.GameManager
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`GameOver`](#gameover)() |
| `void` | [`LevelComplete`](#levelcomplete)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### GameManager
```csharp
public GameManager()
```

### Methods
#### GameOver
```csharp
public void GameOver()
```

#### LevelComplete
```csharp
public void LevelComplete()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
