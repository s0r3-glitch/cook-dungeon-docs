# WaypointGameObject `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph WaypointsFree
  WaypointsFree.WaypointGameObject[[WaypointGameObject]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> WaypointsFree.WaypointGameObject
```

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### WaypointGameObject
```csharp
public WaypointGameObject()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
