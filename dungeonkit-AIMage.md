# AIMage `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.AIMage[[AIMage]]
  DungeonKIT.AICombat[[AICombat]]
  end
DungeonKIT.AICombat --> DungeonKIT.AIMage
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`RangeAttack`](#rangeattack)(`GameObject` rangeWeapon, `Transform` target) |

## Details
### Inheritance
 - [
`AICombat`
](./dungeonkit-AICombat)

### Constructors
#### AIMage
```csharp
public AIMage()
```

### Methods
#### RangeAttack
```csharp
public override void RangeAttack(GameObject rangeWeapon, Transform target)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `GameObject` | rangeWeapon |   |
| `Transform` | target |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
