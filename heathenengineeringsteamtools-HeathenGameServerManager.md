# HeathenGameServerManager `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.HeathenGameServerManager[[HeathenGameServerManager]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> HeathenEngineering.SteamTools.HeathenGameServerManager
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`InitializeGameServer`](#initializegameserver)() |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### HeathenGameServerManager
```csharp
public HeathenGameServerManager()
```

### Methods
#### InitializeGameServer
```csharp
public void InitializeGameServer()
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
