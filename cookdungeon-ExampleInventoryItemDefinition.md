# ExampleInventoryItemDefinition `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.ExampleInventoryItemDefinition[[ExampleInventoryItemDefinition]]
  end
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.InventoryItemDefinition[[InventoryItemDefinition]]
  class HeathenEngineering.SteamTools.InventoryItemDefinition abstractStyle;
  end
HeathenEngineering.SteamTools.InventoryItemDefinition --> CookDungeon.ExampleInventoryItemDefinition
```

## Details
### Inheritance
 - [
`InventoryItemDefinition`
](./heathenengineeringsteamtools-InventoryItemDefinition)

### Constructors
#### ExampleInventoryItemDefinition
```csharp
public ExampleInventoryItemDefinition()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
