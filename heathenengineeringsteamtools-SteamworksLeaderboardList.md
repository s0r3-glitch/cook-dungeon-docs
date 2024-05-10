# SteamworksLeaderboardList `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.SteamworksLeaderboardList[[SteamworksLeaderboardList]]
  end
  subgraph HeathenEngineering.Tools
HeathenEngineering.Tools.HeathenUIBehaviour[[HeathenUIBehaviour]]
  end
HeathenEngineering.Tools.HeathenUIBehaviour --> HeathenEngineering.SteamTools.SteamworksLeaderboardList
```

## Members
### Properties
#### Public  properties
| Type | Name | Methods |
| --- | --- | --- |
| `Nullable`&lt;`LeaderboardEntry_t`&gt; | [`UserEntry`](#userentry) | `get` |

### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`QueryEntries`](#queryentries)(`ELeaderboardDataRequest` requestType, `int` rangeStart, `int` rangeEnd) |
| `void` | [`QueryFriendEntries`](#queryfriendentries)(`int` aroundPlayer) |
| `void` | [`QueryPeerEntries`](#querypeerentries)(`int` aroundPlayer) |
| `void` | [`QueryTopEntries`](#querytopentries)(`int` count) |
| `void` | [`RefreshUserEntry`](#refreshuserentry)() |
| `void` | [`RegisterBoard`](#registerboard)([`SteamworksLeaderboardData`](./heathenengineeringsteamtools-SteamworksLeaderboardData) data) |
| `void` | [`UploadScore`](#uploadscore-12)(`...`) |

## Details
### Inheritance
 - `HeathenUIBehaviour`

### Constructors
#### SteamworksLeaderboardList
```csharp
public SteamworksLeaderboardList()
```

### Methods
#### RegisterBoard
```csharp
public void RegisterBoard(SteamworksLeaderboardData data)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`SteamworksLeaderboardData`](./heathenengineeringsteamtools-SteamworksLeaderboardData) | data |   |

#### UploadScore [1/2]
```csharp
public void UploadScore(int score, ELeaderboardUploadScoreMethod method)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `int` | score |   |
| `ELeaderboardUploadScoreMethod` | method |   |

#### UploadScore [2/2]
```csharp
public void UploadScore(int score, int[] scoreDetails, ELeaderboardUploadScoreMethod method)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `int` | score |   |
| `int``[]` | scoreDetails |   |
| `ELeaderboardUploadScoreMethod` | method |   |

#### QueryEntries
```csharp
public void QueryEntries(ELeaderboardDataRequest requestType, int rangeStart, int rangeEnd)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `ELeaderboardDataRequest` | requestType |   |
| `int` | rangeStart |   |
| `int` | rangeEnd |   |

#### QueryTopEntries
```csharp
public void QueryTopEntries(int count)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `int` | count |   |

#### QueryPeerEntries
```csharp
public void QueryPeerEntries(int aroundPlayer)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `int` | aroundPlayer |   |

#### QueryFriendEntries
```csharp
public void QueryFriendEntries(int aroundPlayer)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `int` | aroundPlayer |   |

#### RefreshUserEntry
```csharp
public void RefreshUserEntry()
```

### Properties
#### UserEntry
```csharp
public Nullable<LeaderboardEntry_t> UserEntry { get; }
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
