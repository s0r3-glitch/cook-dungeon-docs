# SGManager `Public class`

## Description
Stage Manager

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.SGManager[[SGManager]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> CookDungeon.SGManager
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`INLEVEL`](#inlevel)(`Transform` pp, `int` DoorDIR) |

## Details
### Summary
Stage Manager

### Inheritance
 - `MonoBehaviour`

### Constructors
#### SGManager
```csharp
public SGManager()
```

### Methods
#### INLEVEL
```csharp
public void INLEVEL(Transform pp, int DoorDIR)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `Transform` | pp |   |
| `int` | DoorDIR |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
