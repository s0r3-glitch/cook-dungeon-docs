# VirtualJoystick `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.VirtualJoystick[[VirtualJoystick]]
  end
  subgraph UnityEngine.EventSystems
UnityEngine.EventSystems.IDragHandler[[IDragHandler]]
UnityEngine.EventSystems.IEventSystemHandler[[IEventSystemHandler]]
UnityEngine.EventSystems.IPointerUpHandler[[IPointerUpHandler]]
UnityEngine.EventSystems.IPointerDownHandler[[IPointerDownHandler]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.EventSystems.IDragHandler --> DungeonKIT.VirtualJoystick
UnityEngine.EventSystems.IEventSystemHandler --> DungeonKIT.VirtualJoystick
UnityEngine.EventSystems.IPointerUpHandler --> DungeonKIT.VirtualJoystick
UnityEngine.EventSystems.IPointerDownHandler --> DungeonKIT.VirtualJoystick
UnityEngine.MonoBehaviour --> DungeonKIT.VirtualJoystick
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`OnDrag`](#ondrag)(`PointerEventData` eventData) |
| `void` | [`OnPointerDown`](#onpointerdown)(`PointerEventData` eventData) |
| `void` | [`OnPointerUp`](#onpointerup)(`PointerEventData` eventData) |

## Details
### Inheritance
 - `IDragHandler`
 - `IEventSystemHandler`
 - `IPointerUpHandler`
 - `IPointerDownHandler`
 - `MonoBehaviour`

### Nested types
#### Enums
 - `JoystickType`

### Constructors
#### VirtualJoystick
```csharp
public VirtualJoystick()
```

### Methods
#### OnPointerDown
```csharp
public virtual void OnPointerDown(PointerEventData eventData)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `PointerEventData` | eventData |   |

#### OnDrag
```csharp
public virtual void OnDrag(PointerEventData eventData)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `PointerEventData` | eventData |   |

#### OnPointerUp
```csharp
public virtual void OnPointerUp(PointerEventData eventData)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `PointerEventData` | eventData |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
