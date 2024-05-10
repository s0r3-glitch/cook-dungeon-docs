# HeathenLeaderboardStatTool `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.HeathenLeaderboardStatTool[[HeathenLeaderboardStatTool]]
  end
  subgraph HeathenEngineering.Tools
HeathenEngineering.Tools.HeathenBehaviour[[HeathenBehaviour]]
  end
HeathenEngineering.Tools.HeathenBehaviour --> HeathenEngineering.SteamTools.HeathenLeaderboardStatTool
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`Submit`](#submit)() |

## Details
### Inheritance
 - `HeathenBehaviour`

### Constructors
#### HeathenLeaderboardStatTool
```csharp
public HeathenLeaderboardStatTool()
```

### Methods
#### Submit
```csharp
public void Submit()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
