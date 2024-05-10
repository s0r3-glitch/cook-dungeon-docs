# CPXX `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.CPXX[[CPXX]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.CPXX
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`DP`](#dp)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### CPXX
```csharp
public CPXX()
```

### Methods
#### DP
```csharp
public void DP()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
