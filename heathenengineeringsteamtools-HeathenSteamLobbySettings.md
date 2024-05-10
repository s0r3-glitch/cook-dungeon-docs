# HeathenSteamLobbySettings `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.HeathenSteamLobbySettings[[HeathenSteamLobbySettings]]
  end
  subgraph UnityEngine
UnityEngine.ScriptableObject[[ScriptableObject]]
  end
UnityEngine.ScriptableObject --> HeathenEngineering.SteamTools.HeathenSteamLobbySettings
```

## Members
### Properties
#### Public  properties
| Type | Name | Methods |
| --- | --- | --- |
| `bool` | [`HasLobby`](#haslobby) | `get` |
| `bool` | [`InLobby`](#inlobby) | `get` |
| `bool` | [`IsHost`](#ishost) | `get` |
| `bool` | [`IsQuickSearching`](#isquicksearching) | `get` |
| `bool` | [`IsSearching`](#issearching) | `get` |
| `CSteamID` | [`lobbyId`](#lobbyid) | `get` |

### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`CancelQuickMatch`](#cancelquickmatch)() |
| `void` | [`CancelStandardSearch`](#cancelstandardsearch)() |
| `void` | [`CreateLobby`](#createlobby)([`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) LobbyFilter, `string` LobbyName, `ELobbyType` lobbyType) |
| `void` | [`FindMatch`](#findmatch)([`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) LobbyFilter) |
| `void` | [`JoinLobby`](#joinlobby-12)(`...`) |
| `void` | [`LeaveLobby`](#leavelobby)() |
| [`LobbyMember`](./heathenengineeringsteamtools-LobbyMember) | [`ProcessLobbyMember`](#processlobbymember)(`CSteamID` memberId) |
| `bool` | [`QuickMatch`](#quickmatch)([`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) LobbyFilter, `string` onCreateName, `bool` autoCreate) |
| `void` | [`RegisterCallbacks`](#registercallbacks)() |
| `bool` | [`RemoveMember`](#removemember)(`CSteamID` memberId) |
| `void` | [`SendChatMessage`](#sendchatmessage)(`string` message) |
| `void` | [`SetLobbyGameServer`](#setlobbygameserver-13)(`...`) |
| `void` | [`SetLobbyId`](#setlobbyid)(`CSteamID` lobbyId) |
| `void` | [`SetLobbyMetadata`](#setlobbymetadata)(`string` key, `string` value) |
| `void` | [`SetMemberMetadata`](#setmembermetadata)(`string` key, `string` value) |

## Details
### Inheritance
 - `ScriptableObject`

### Constructors
#### HeathenSteamLobbySettings
```csharp
public HeathenSteamLobbySettings()
```

### Methods
#### RegisterCallbacks
```csharp
public void RegisterCallbacks()
```

#### SetLobbyId
```csharp
public void SetLobbyId(CSteamID lobbyId)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `CSteamID` | lobbyId |   |

#### RemoveMember
```csharp
public bool RemoveMember(CSteamID memberId)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `CSteamID` | memberId |   |

#### ProcessLobbyMember
```csharp
public LobbyMember ProcessLobbyMember(CSteamID memberId)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `CSteamID` | memberId |   |

#### CreateLobby
```csharp
public void CreateLobby(LobbyHunterFilter LobbyFilter, string LobbyName, ELobbyType lobbyType)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) | LobbyFilter |   |
| `string` | LobbyName |   |
| `ELobbyType` | lobbyType |   |

#### JoinLobby [1/2]
```csharp
public void JoinLobby(CSteamID lobbyId)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `CSteamID` | lobbyId |   |

#### JoinLobby [2/2]
```csharp
public void JoinLobby(ulong lobbyId)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `ulong` | lobbyId |   |

#### LeaveLobby
```csharp
public void LeaveLobby()
```

#### FindMatch
```csharp
public void FindMatch(LobbyHunterFilter LobbyFilter)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) | LobbyFilter |   |

#### QuickMatch
```csharp
public bool QuickMatch(LobbyHunterFilter LobbyFilter, string onCreateName, bool autoCreate)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| [`LobbyHunterFilter`](./heathenengineeringsteamtools-LobbyHunterFilter) | LobbyFilter |   |
| `string` | onCreateName |   |
| `bool` | autoCreate |   |

#### CancelQuickMatch
```csharp
public void CancelQuickMatch()
```

#### CancelStandardSearch
```csharp
public void CancelStandardSearch()
```

#### SendChatMessage
```csharp
public void SendChatMessage(string message)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | message |   |

#### SetLobbyMetadata
```csharp
public void SetLobbyMetadata(string key, string value)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | key |   |
| `string` | value |   |

#### SetMemberMetadata
```csharp
public void SetMemberMetadata(string key, string value)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | key |   |
| `string` | value |   |

#### SetLobbyGameServer [1/3]
```csharp
public void SetLobbyGameServer()
```

#### SetLobbyGameServer [2/3]
```csharp
public void SetLobbyGameServer(CSteamID gameServerId)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `CSteamID` | gameServerId |   |

#### SetLobbyGameServer [3/3]
```csharp
public void SetLobbyGameServer(uint ipAddress, ushort port)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `uint` | ipAddress |   |
| `ushort` | port |   |

### Properties
#### InLobby
```csharp
public bool InLobby { get; }
```

#### HasLobby
```csharp
public bool HasLobby { get; }
```

#### IsHost
```csharp
public bool IsHost { get; }
```

#### IsSearching
```csharp
public bool IsSearching { get; }
```

#### IsQuickSearching
```csharp
public bool IsQuickSearching { get; }
```

#### lobbyId
```csharp
public CSteamID lobbyId { get; }
```

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
