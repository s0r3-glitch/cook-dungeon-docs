# SteamFloatStatData `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.SteamFloatStatData[[SteamFloatStatData]]
  HeathenEngineering.SteamTools.SteamStatData[[SteamStatData]]
  class HeathenEngineering.SteamTools.SteamStatData abstractStyle;
  end
HeathenEngineering.SteamTools.SteamStatData --> HeathenEngineering.SteamTools.SteamFloatStatData
```

## Members
### Properties
#### Public  properties
| Type | Name | Methods |
| --- | --- | --- |
| `StatDataType` | [`DataType`](#datatype) | `get` |

### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `float` | [`GetFloatValue`](#getfloatvalue)() |
| `int` | [`GetIntValue`](#getintvalue)() |
| `void` | [`SetFloatStat`](#setfloatstat)(`float` value) |
| `void` | [`SetIntStat`](#setintstat)(`int` value) |
| `void` | [`UpdateValue`](#updatevalue-12)(`...`) |

## Details
### Inheritance
 - [
`SteamStatData`
](./heathenengineeringsteamtools-SteamStatData)

### Constructors
#### SteamFloatStatData
```csharp
public SteamFloatStatData()
```

### Methods
#### GetFloatValue
```csharp
public override float GetFloatValue()
```

#### GetIntValue
```csharp
public override int GetIntValue()
```

#### SetFloatStat
```csharp
public override void SetFloatStat(float value)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `float` | value |   |

#### SetIntStat
```csharp
public override void SetIntStat(int value)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `int` | value |   |

#### UpdateValue [1/2]
```csharp
public override void UpdateValue(int value)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `int` | value |   |

#### UpdateValue [2/2]
```csharp
public override void UpdateValue(float value)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `float` | value |   |

### Properties
#### DataType
```csharp
public override StatDataType DataType { get; }
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
