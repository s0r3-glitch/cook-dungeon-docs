# SteamUserFullIcon `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.SteamUserFullIcon[[SteamUserFullIcon]]
  end
  subgraph HeathenEngineering.Tools
HeathenEngineering.Tools.HeathenUIBehaviour[[HeathenUIBehaviour]]
  end
HeathenEngineering.Tools.HeathenUIBehaviour --> HeathenEngineering.SteamTools.SteamUserFullIcon
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`LinkSteamUser`](#linksteamuser)([`SteamUserData`](./heathenengineeringsteamtools-SteamUserData) newUserData) |

## Details
### Inheritance
 - `HeathenUIBehaviour`

### Constructors
#### SteamUserFullIcon
```csharp
public SteamUserFullIcon()
```

### Methods
#### LinkSteamUser
```csharp
public void LinkSteamUser(SteamUserData newUserData)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`SteamUserData`](./heathenengineeringsteamtools-SteamUserData) | newUserData |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
