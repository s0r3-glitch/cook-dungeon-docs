# Shock `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.Shock[[Shock]]
  end
  subgraph DungeonKIT
  DungeonKIT.AICombat[[AICombat]]
  end
DungeonKIT.AICombat --> CookDungeon.Shock
```

## Details
### Inheritance
 - [
`AICombat`
](./dungeonkit-AICombat)

### Constructors
#### Shock
```csharp
public Shock()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
