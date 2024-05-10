# Demo `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.Demo[[Demo]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.Demo
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`Update`](#update)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### Demo
```csharp
public Demo()
```

### Methods
#### Update
```csharp
public void Update()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
