# ExampleLobbyRecord `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.ExampleLobbyRecord[[ExampleLobbyRecord]]
  end
  subgraph HeathenEngineering.SteamTools
HeathenEngineering.SteamTools.LobbyRecordBehvaiour[[LobbyRecordBehvaiour]]
  end
HeathenEngineering.SteamTools.LobbyRecordBehvaiour --> CookDungeon.ExampleLobbyRecord
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`Selected`](#selected)() |
| `void` | [`SetLobby`](#setlobby)(`LobbyHunterLobbyRecord` record, `HeathenSteamLobbySettings` lobbySettings) |

## Details
### Inheritance
 - `LobbyRecordBehvaiour`

### Constructors
#### ExampleLobbyRecord
```csharp
public ExampleLobbyRecord()
```

### Methods
#### SetLobby
```csharp
public override void SetLobby(LobbyHunterLobbyRecord record, HeathenSteamLobbySettings lobbySettings)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `LobbyHunterLobbyRecord` | record |   |
| `HeathenSteamLobbySettings` | lobbySettings |   |

#### Selected
```csharp
public void Selected()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
