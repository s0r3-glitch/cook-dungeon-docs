# WaypointsTraveler `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph WaypointsFree
  WaypointsFree.WaypointsTraveler[[WaypointsTraveler]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> WaypointsFree.WaypointsTraveler
```

## Members
### Properties
#### Public  properties
| Type | Name | Methods |
| --- | --- | --- |
| `bool` | [`IsMoving`](#ismoving) | `get` |

### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`Move`](#move)(`bool` tf) |
| `void` | [`ResetTraveler`](#resettraveler)() |
| `void` | [`SetWaypointsGroup`](#setwaypointsgroup)([`WaypointsGroup`](./waypointsfree-WaypointsGroup) newGroup) |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### WaypointsTraveler
```csharp
public WaypointsTraveler()
```

### Methods
#### ResetTraveler
```csharp
public void ResetTraveler()
```

#### Move
```csharp
public void Move(bool tf)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `bool` | tf |   |

#### SetWaypointsGroup
```csharp
public void SetWaypointsGroup(WaypointsGroup newGroup)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`WaypointsGroup`](./waypointsfree-WaypointsGroup) | newGroup |   |

### Properties
#### IsMoving
```csharp
public bool IsMoving { get; }
```

### Delegates
#### MovementFunction
```csharp
internal delegate bool MovementFunction()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
