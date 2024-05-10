# HeathenSteamLobbyChat `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.HeathenSteamLobbyChat[[HeathenSteamLobbyChat]]
  end
  subgraph HeathenEngineering.Tools
HeathenEngineering.Tools.HeathenUIBehaviour[[HeathenUIBehaviour]]
  end
HeathenEngineering.Tools.HeathenUIBehaviour --> HeathenEngineering.SteamTools.HeathenSteamLobbyChat
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`RefreshTimeStampSettings`](#refreshtimestampsettings)() |
| `void` | [`SendChatMessage`](#sendchatmessage-12)(`...`) |

## Details
### Inheritance
 - `HeathenUIBehaviour`

### Constructors
#### HeathenSteamLobbyChat
```csharp
public HeathenSteamLobbyChat()
```

### Methods
#### RefreshTimeStampSettings
```csharp
public void RefreshTimeStampSettings()
```

#### SendChatMessage [1/2]
```csharp
public void SendChatMessage(string message)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | message |   |

#### SendChatMessage [2/2]
```csharp
public void SendChatMessage()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
