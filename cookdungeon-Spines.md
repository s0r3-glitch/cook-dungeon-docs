# Spines `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph CookDungeon
  CookDungeon.Spines[[Spines]]
  end
  subgraph DungeonKIT
  DungeonKIT.AICombat[[AICombat]]
  end
DungeonKIT.AICombat --> CookDungeon.Spines
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`FixSHurt`](#fixshurt)() |
| `void` | [`SetCanHurt`](#setcanhurt)() |
| `void` | [`SetNoHurt`](#setnohurt)() |

## Details
### Inheritance
 - [
`AICombat`
](./dungeonkit-AICombat)

### Constructors
#### Spines
```csharp
public Spines()
```

### Methods
#### SetCanHurt
```csharp
public void SetCanHurt()
```

#### SetNoHurt
```csharp
public void SetNoHurt()
```

#### FixSHurt
```csharp
public void FixSHurt()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
