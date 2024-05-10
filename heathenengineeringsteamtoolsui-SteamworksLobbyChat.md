# SteamworksLobbyChat `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools.UI
  HeathenEngineering.SteamTools.UI.SteamworksLobbyChat[[SteamworksLobbyChat]]
  end
  subgraph HeathenEngineering.Tools
HeathenEngineering.Tools.HeathenUIBehaviour[[HeathenUIBehaviour]]
  end
HeathenEngineering.Tools.HeathenUIBehaviour --> HeathenEngineering.SteamTools.UI.SteamworksLobbyChat
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`ClearMessages`](#clearmessages)() |
| `void` | [`SendChatMessage`](#sendchatmessage-12)(`...`) |
| `void` | [`SendSystemMessage`](#sendsystemmessage)(`string` sender, `string` message) |

## Details
### Inheritance
 - `HeathenUIBehaviour`

### Constructors
#### SteamworksLobbyChat
```csharp
public SteamworksLobbyChat()
```

### Methods
#### ClearMessages
```csharp
public void ClearMessages()
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

#### SendSystemMessage
```csharp
public void SendSystemMessage(string sender, string message)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | sender |   |
| `string` | message |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
