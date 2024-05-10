# HeathenSteamLeaderboardEntry `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.HeathenSteamLeaderboardEntry[[HeathenSteamLeaderboardEntry]]
  end
  subgraph HeathenEngineering.Tools
HeathenEngineering.Tools.HeathenUIBehaviour[[HeathenUIBehaviour]]
  end
HeathenEngineering.Tools.HeathenUIBehaviour --> HeathenEngineering.SteamTools.HeathenSteamLeaderboardEntry
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`ApplyEntry`](#applyentry)([`ExtendedLeaderboardEntry`](./heathenengineeringsteamtools-ExtendedLeaderboardEntry) entry) |

## Details
### Inheritance
 - `HeathenUIBehaviour`

### Constructors
#### HeathenSteamLeaderboardEntry
```csharp
public HeathenSteamLeaderboardEntry()
```

### Methods
#### ApplyEntry
```csharp
public virtual void ApplyEntry(ExtendedLeaderboardEntry entry)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`ExtendedLeaderboardEntry`](./heathenengineeringsteamtools-ExtendedLeaderboardEntry) | entry |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
