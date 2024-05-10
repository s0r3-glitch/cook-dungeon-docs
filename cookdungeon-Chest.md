# Chest `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.Chest[[Chest]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.Chest
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`DisTreasure`](#distreasure)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### Chest
```csharp
public Chest()
```

### Methods
#### DisTreasure
```csharp
public void DisTreasure()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
