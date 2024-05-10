# Ticket `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools.SteamworksAuthentication
  HeathenEngineering.SteamTools.SteamworksAuthentication.Ticket[[Ticket]]
  end
```

## Members
### Properties
#### Public  properties
| Type | Name | Methods |
| --- | --- | --- |
| `TimeSpan` | [`Age`](#age) | `get` |

### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`Cancel`](#cancel)() |

## Details
### Constructors
#### Ticket
```csharp
public Ticket()
```

### Methods
#### Cancel
```csharp
public void Cancel()
```

### Properties
#### Age
```csharp
public TimeSpan Age { get; }
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
