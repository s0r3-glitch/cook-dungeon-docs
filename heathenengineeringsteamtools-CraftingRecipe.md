# CraftingRecipe `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.CraftingRecipe[[CraftingRecipe]]
  end
  subgraph UnityEngine
UnityEngine.ScriptableObject[[ScriptableObject]]
  end
UnityEngine.ScriptableObject --> HeathenEngineering.SteamTools.CraftingRecipe
```

## Details
### Inheritance
 - `ScriptableObject`

### Constructors
#### CraftingRecipe
```csharp
public CraftingRecipe()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
