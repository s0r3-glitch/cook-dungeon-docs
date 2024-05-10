# SteamAchievementData `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.SteamAchievementData[[SteamAchievementData]]
  end
  subgraph UnityEngine
UnityEngine.ScriptableObject[[ScriptableObject]]
  end
UnityEngine.ScriptableObject --> HeathenEngineering.SteamTools.SteamAchievementData
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`Unlock`](#unlock)() |

## Details
### Inheritance
 - `ScriptableObject`

### Constructors
#### SteamAchievementData
```csharp
public SteamAchievementData()
```

### Methods
#### Unlock
```csharp
public void Unlock()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
