# PRINCESS `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.PRINCESS[[PRINCESS]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.PRINCESS
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`End`](#end)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### PRINCESS
```csharp
public PRINCESS()
```

### Methods
#### End
```csharp
public void End()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
