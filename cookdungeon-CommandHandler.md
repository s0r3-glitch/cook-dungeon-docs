# CommandHandler `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.CommandHandler[[CommandHandler]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.CommandHandler
```

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### CommandHandler
```csharp
public CommandHandler()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
