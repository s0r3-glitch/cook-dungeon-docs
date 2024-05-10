# SteamUserIconButton `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.SteamUserIconButton[[SteamUserIconButton]]
  HeathenEngineering.SteamTools.SteamUserFullIcon[[SteamUserFullIcon]]
  end
  subgraph UnityEngine.EventSystems
UnityEngine.EventSystems.IPointerClickHandler[[IPointerClickHandler]]
UnityEngine.EventSystems.IEventSystemHandler[[IEventSystemHandler]]
  end
UnityEngine.EventSystems.IPointerClickHandler --> HeathenEngineering.SteamTools.SteamUserIconButton
UnityEngine.EventSystems.IEventSystemHandler --> HeathenEngineering.SteamTools.SteamUserIconButton
HeathenEngineering.SteamTools.SteamUserFullIcon --> HeathenEngineering.SteamTools.SteamUserIconButton
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`OnPointerClick`](#onpointerclick)(`PointerEventData` eventData) |

## Details
### Inheritance
 - `IPointerClickHandler`
 - `IEventSystemHandler`
 - [
`SteamUserFullIcon`
](./heathenengineeringsteamtools-SteamUserFullIcon)

### Constructors
#### SteamUserIconButton
```csharp
public SteamUserIconButton()
```

### Methods
#### OnPointerClick
```csharp
public virtual void OnPointerClick(PointerEventData eventData)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `PointerEventData` | eventData |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
