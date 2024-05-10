# SpawnProjectiles `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.SpawnProjectiles[[SpawnProjectiles]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.SpawnProjectiles
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`Spawn`](#spawn)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### SpawnProjectiles
```csharp
public SpawnProjectiles()
```

### Methods
#### Spawn
```csharp
public void Spawn()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
