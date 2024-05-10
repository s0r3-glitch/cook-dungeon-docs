# HeathenChatMessage `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.HeathenChatMessage[[HeathenChatMessage]]
  end
  subgraph UnityEngine.EventSystems
UnityEngine.EventSystems.IPointerEnterHandler[[IPointerEnterHandler]]
UnityEngine.EventSystems.IEventSystemHandler[[IEventSystemHandler]]
UnityEngine.EventSystems.IPointerExitHandler[[IPointerExitHandler]]
  end
  subgraph HeathenEngineering.Tools
HeathenEngineering.Tools.HeathenUIBehaviour[[HeathenUIBehaviour]]
  end
UnityEngine.EventSystems.IPointerEnterHandler --> HeathenEngineering.SteamTools.HeathenChatMessage
UnityEngine.EventSystems.IEventSystemHandler --> HeathenEngineering.SteamTools.HeathenChatMessage
UnityEngine.EventSystems.IPointerExitHandler --> HeathenEngineering.SteamTools.HeathenChatMessage
HeathenEngineering.Tools.HeathenUIBehaviour --> HeathenEngineering.SteamTools.HeathenChatMessage
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`OnPointerEnter`](#onpointerenter)(`PointerEventData` eventData) |
| `void` | [`OnPointerExit`](#onpointerexit)(`PointerEventData` eventData) |

## Details
### Inheritance
 - `IPointerEnterHandler`
 - `IEventSystemHandler`
 - `IPointerExitHandler`
 - `HeathenUIBehaviour`

### Constructors
#### HeathenChatMessage
```csharp
public HeathenChatMessage()
```

### Methods
#### OnPointerEnter
```csharp
public virtual void OnPointerEnter(PointerEventData eventData)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `PointerEventData` | eventData |   |

#### OnPointerExit
```csharp
public virtual void OnPointerExit(PointerEventData eventData)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `PointerEventData` | eventData |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
