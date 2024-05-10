# SteamworksLobbyManager `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.SteamworksLobbyManager[[SteamworksLobbyManager]]
  HeathenEngineering.SteamTools.ISteamworksLobbyManager[[ISteamworksLobbyManager]]
  class HeathenEngineering.SteamTools.ISteamworksLobbyManager interfaceStyle;
  end
  subgraph HeathenEngineering.Tools
HeathenEngineering.Tools.HeathenBehaviour[[HeathenBehaviour]]
  end
HeathenEngineering.SteamTools.ISteamworksLobbyManager --> HeathenEngineering.SteamTools.SteamworksLobbyManager
HeathenEngineering.Tools.HeathenBehaviour --> HeathenEngineering.SteamTools.SteamworksLobbyManager
```

## Members
### Properties
#### Public  properties
| Type | Name | Methods |
| --- | --- | --- |
| `bool` | [`IsQuickSearching`](#isquicksearching) | `get` |
| `bool` | [`IsSearching`](#issearching) | `get` |

### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`CancelQuickMatch`](#cancelquickmatch)() |
| `void` | [`CancelStandardSearch`](#cancelstandardsearch)() |
| `void` | [`CreateLobby`](#createlobby)([`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) LobbyFilter, `string` LobbyName, `ELobbyType` lobbyType) |
| `void` | [`FindMatch`](#findmatch)([`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) LobbyFilter) |
| `void` | [`JoinLobby`](#joinlobby)(`CSteamID` lobbyId) |
| `void` | [`LeaveLobby`](#leavelobby)() |
| `bool` | [`QuickMatch`](#quickmatch)([`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) LobbyFilter, `string` onCreateName, `bool` autoCreate) |
| `void` | [`SendChatMessage`](#sendchatmessage)(`string` message) |
| `void` | [`SetLobbyGameServer`](#setlobbygameserver)() |
| `void` | [`SetLobbyMetadata`](#setlobbymetadata)(`string` key, `string` value) |
| `void` | [`SetMemberMetadata`](#setmembermetadata)(`string` key, `string` value) |

## Details
### Inheritance
 - [
`ISteamworksLobbyManager`
](./heathenengineeringsteamtools-ISteamworksLobbyManager)
 - `HeathenBehaviour`

### Constructors
#### SteamworksLobbyManager
```csharp
public SteamworksLobbyManager()
```

### Methods
#### CreateLobby
```csharp
public virtual void CreateLobby(LobbyHunterFilter LobbyFilter, string LobbyName, ELobbyType lobbyType)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) | LobbyFilter |   |
| `string` | LobbyName |   |
| `ELobbyType` | lobbyType |   |

#### JoinLobby
```csharp
public virtual void JoinLobby(CSteamID lobbyId)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `CSteamID` | lobbyId |   |

#### LeaveLobby
```csharp
public virtual void LeaveLobby()
```

#### FindMatch
```csharp
public virtual void FindMatch(LobbyHunterFilter LobbyFilter)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) | LobbyFilter |   |

#### QuickMatch
```csharp
public virtual bool QuickMatch(LobbyHunterFilter LobbyFilter, string onCreateName, bool autoCreate)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) | LobbyFilter |   |
| `string` | onCreateName |   |
| `bool` | autoCreate |   |

#### CancelQuickMatch
```csharp
public virtual void CancelQuickMatch()
```

#### CancelStandardSearch
```csharp
public virtual void CancelStandardSearch()
```

#### SendChatMessage
```csharp
public virtual void SendChatMessage(string message)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | message |   |

#### SetLobbyMetadata
```csharp
public virtual void SetLobbyMetadata(string key, string value)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | key |   |
| `string` | value |   |

#### SetMemberMetadata
```csharp
public virtual void SetMemberMetadata(string key, string value)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | key |   |
| `string` | value |   |

#### SetLobbyGameServer
```csharp
public virtual void SetLobbyGameServer()
```

### Properties
#### IsSearching
```csharp
public virtual bool IsSearching { get; }
```

#### IsQuickSearching
```csharp
public virtual bool IsQuickSearching { get; }
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
