# DDD `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.DDD[[DDD]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.DDD
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`B`](#b)() |
| `void` | [`D`](#d)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### DDD
```csharp
public DDD()
```

### Methods
#### D
```csharp
public void D()
```

#### B
```csharp
public void B()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
