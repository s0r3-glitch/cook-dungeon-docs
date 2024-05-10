# RangeWeapon `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.RangeWeapon[[RangeWeapon]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> DungeonKIT.RangeWeapon
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`Destroying`](#destroying)() |
| `void` | [`OnTriggerEnter2D`](#ontriggerenter2d)(`Collider2D` collider) |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### RangeWeapon
```csharp
public RangeWeapon()
```

### Methods
#### OnTriggerEnter2D
```csharp
public virtual void OnTriggerEnter2D(Collider2D collider)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `Collider2D` | collider |   |

#### Destroying
```csharp
public void Destroying()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
