# FOGS `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.FOGS[[FOGS]]
  end
  subgraph DungeonKIT
  DungeonKIT.AICombat[[AICombat]]
  end
DungeonKIT.AICombat --> CookDungeon.FOGS
```

## Details
### Inheritance
 - [
`AICombat`
](./dungeonkit-AICombat)

### Constructors
#### FOGS
```csharp
public FOGS()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
