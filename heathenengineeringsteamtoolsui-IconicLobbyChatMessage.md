# IconicLobbyChatMessage `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools.UI
  HeathenEngineering.SteamTools.UI.IconicLobbyChatMessage[[IconicLobbyChatMessage]]
  HeathenEngineering.SteamTools.UI.ILobbyChatMessage[[ILobbyChatMessage]]
  class HeathenEngineering.SteamTools.UI.ILobbyChatMessage interfaceStyle;
  end
  subgraph HeathenEngineering.Tools
HeathenEngineering.Tools.HeathenUIBehaviour[[HeathenUIBehaviour]]
  end
HeathenEngineering.SteamTools.UI.ILobbyChatMessage --> HeathenEngineering.SteamTools.UI.IconicLobbyChatMessage
HeathenEngineering.Tools.HeathenUIBehaviour --> HeathenEngineering.SteamTools.UI.IconicLobbyChatMessage
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`OnPointerEnter`](#onpointerenter)(`PointerEventData` eventData) |
| `void` | [`OnPointerExit`](#onpointerexit)(`PointerEventData` eventData) |
| `void` | [`RegisterChatMessage`](#registerchatmessage)([`LobbyChatMessageData`](./heathenengineeringsteamtools-LobbyChatMessageData) data) |
| `void` | [`SetMessageText`](#setmessagetext)(`string` sender, `string` message) |

## Details
### Inheritance
 - [
`ILobbyChatMessage`
](./heathenengineeringsteamtoolsui-ILobbyChatMessage)
 - `HeathenUIBehaviour`

### Constructors
#### IconicLobbyChatMessage
```csharp
public IconicLobbyChatMessage()
```

### Methods
#### OnPointerEnter
```csharp
public void OnPointerEnter(PointerEventData eventData)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `PointerEventData` | eventData |   |

#### OnPointerExit
```csharp
public void OnPointerExit(PointerEventData eventData)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `PointerEventData` | eventData |   |

#### RegisterChatMessage
```csharp
public virtual void RegisterChatMessage(LobbyChatMessageData data)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`LobbyChatMessageData`](./heathenengineeringsteamtools-LobbyChatMessageData) | data |   |

#### SetMessageText
```csharp
public virtual void SetMessageText(string sender, string message)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | sender |   |
| `string` | message |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
