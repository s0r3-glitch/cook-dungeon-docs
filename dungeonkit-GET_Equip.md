# GET_Equip `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph DungeonKIT
  DungeonKIT.GET_Equip[[GET_Equip]]
  DungeonKIT.Item[[Item]]
  end
DungeonKIT.Item --> DungeonKIT.GET_Equip
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`FindASlot`](#findaslot)(`int` num) |
| `void` | [`OnPickedUp`](#onpickedup)() |
| `void` | [`OnTriggerEnter2D`](#ontriggerenter2d)(`Collider2D` collision) |

## Details
### Inheritance
 - [
`Item`
](./dungeonkit-Item)

### Constructors
#### GET_Equip
```csharp
public GET_Equip()
```

### Methods
#### OnPickedUp
```csharp
public void OnPickedUp()
```

#### FindASlot
```csharp
public void FindASlot(int num)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `int` | num |   |

#### OnTriggerEnter2D
```csharp
public override void OnTriggerEnter2D(Collider2D collision)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `Collider2D` | collision |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
