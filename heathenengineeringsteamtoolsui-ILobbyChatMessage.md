# ILobbyChatMessage `Public interface`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools.UI
  HeathenEngineering.SteamTools.UI.ILobbyChatMessage[[ILobbyChatMessage]]
  class HeathenEngineering.SteamTools.UI.ILobbyChatMessage interfaceStyle;
  end
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`RegisterChatMessage`](#registerchatmessage)([`LobbyChatMessageData`](./heathenengineeringsteamtools-LobbyChatMessageData) data) |
| `void` | [`SetMessageText`](#setmessagetext)(`string` sender, `string` message) |

## Details
### Methods
#### RegisterChatMessage
```csharp
public void RegisterChatMessage(LobbyChatMessageData data)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`LobbyChatMessageData`](./heathenengineeringsteamtools-LobbyChatMessageData) | data |   |

#### SetMessageText
```csharp
public void SetMessageText(string sender, string message)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | sender |   |
| `string` | message |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
