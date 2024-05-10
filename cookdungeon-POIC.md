# POIC `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.POIC[[POIC]]
  end
  subgraph DungeonKIT
  DungeonKIT.AICombat[[AICombat]]
  end
DungeonKIT.AICombat --> CookDungeon.POIC
```

## Details
### Inheritance
 - [
`AICombat`
](./dungeonkit-AICombat)

### Constructors
#### POIC
```csharp
public POIC()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
