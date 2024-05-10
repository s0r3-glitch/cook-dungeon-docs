# HitIndicator `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.HitIndicator[[HitIndicator]]
  end
  subgraph HeathenEngineering.Tools
HeathenEngineering.Tools.IDamageHandler_1[[IDamageHandler]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
HeathenEngineering.Tools.IDamageHandler_1 --> CookDungeon.HitIndicator
UnityEngine.MonoBehaviour --> CookDungeon.HitIndicator
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`ApplyDamage`](#applydamage)(`Report` data) |
| `void` | [`Update`](#update)() |

## Details
### Inheritance
 - `IDamageHandler`&lt;`Report`&gt;
 - `MonoBehaviour`

### Constructors
#### HitIndicator
```csharp
public HitIndicator()
```

### Methods
#### Update
```csharp
public void Update()
```

#### ApplyDamage
```csharp
public virtual void ApplyDamage(Report data)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `Report` | data |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
