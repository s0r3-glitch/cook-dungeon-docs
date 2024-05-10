# PlayerPPAR `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.PlayerPPAR[[PlayerPPAR]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.PlayerPPAR
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`SetPPAR`](#setppar)(`int` k) |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### PlayerPPAR
```csharp
public PlayerPPAR()
```

### Methods
#### SetPPAR
```csharp
public void SetPPAR(int k)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `int` | k |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
