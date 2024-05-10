# AIOrcBoss `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.AIOrcBoss[[AIOrcBoss]]
  DungeonKIT.AICombat[[AICombat]]
  end
DungeonKIT.AICombat --> DungeonKIT.AIOrcBoss
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`MeleeAttack`](#meleeattack)(`GameObject` target) |

## Details
### Inheritance
 - [
`AICombat`
](./dungeonkit-AICombat)

### Constructors
#### AIOrcBoss
```csharp
public AIOrcBoss()
```

### Methods
#### MeleeAttack
```csharp
public override void MeleeAttack(GameObject target)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `GameObject` | target |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
