# Fires `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.Fires[[Fires]]
  end
  subgraph DungeonKIT
  DungeonKIT.AICombat[[AICombat]]
  end
DungeonKIT.AICombat --> CookDungeon.Fires
```

## Details
### Inheritance
 - [
`AICombat`
](./dungeonkit-AICombat)

### Constructors
#### Fires
```csharp
public Fires()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
