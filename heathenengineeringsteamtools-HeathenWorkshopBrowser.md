# HeathenWorkshopBrowser `Public class`

## Diagram
```mermaid
  flowchart LR
  classDef interfaceStyle stroke-dasharray: 5 5;
  classDef abstractStyle stroke-width:4px
  subgraph HeathenEngineering.SteamTools
  HeathenEngineering.SteamTools.HeathenWorkshopBrowser[[HeathenWorkshopBrowser]]
  end
  subgraph UnityEngine
UnityEngine.MonoBehaviour[[MonoBehaviour]]
  end
UnityEngine.MonoBehaviour --> HeathenEngineering.SteamTools.HeathenWorkshopBrowser
```

## Members
### Methods
#### Public  methods
| Returns | Name |
| --- | --- |
| `void` | [`ExeuctePreparedSearch`](#exeuctepreparedsearch)() |
| `void` | [`PrepareSearchAll`](#preparesearchall)(`string` filter) |
| `void` | [`PrepareSearchFavorites`](#preparesearchfavorites)(`string` filter) |
| `void` | [`PrepareSearchFollowed`](#preparesearchfollowed)(`string` filter) |
| `void` | [`SearchAll`](#searchall)(`string` filter) |
| `void` | [`SearchAllFromInput`](#searchallfrominput)() |
| `void` | [`SearchFavorites`](#searchfavorites)(`string` filter) |
| `void` | [`SearchFavoritesFromInput`](#searchfavoritesfrominput)() |
| `void` | [`SearchFollowed`](#searchfollowed)(`string` filter) |
| `void` | [`SearchFollowedFromInput`](#searchfollowedfrominput)() |
| `void` | [`SetNextSearchPage`](#setnextsearchpage)() |
| `void` | [`SetPreviousSearchPage`](#setprevioussearchpage)() |
| `void` | [`SetSearchPage`](#setsearchpage)(`uint` page) |

## Details
### Inheritance
 - `MonoBehaviour`

### Constructors
#### HeathenWorkshopBrowser
```csharp
public HeathenWorkshopBrowser()
```

### Methods
#### SearchAllFromInput
```csharp
public void SearchAllFromInput()
```

#### SearchAll
```csharp
public void SearchAll(string filter)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | filter |   |

#### PrepareSearchAll
```csharp
public void PrepareSearchAll(string filter)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | filter |   |

#### SearchFavoritesFromInput
```csharp
public void SearchFavoritesFromInput()
```

#### SearchFavorites
```csharp
public void SearchFavorites(string filter)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | filter |   |

#### PrepareSearchFavorites
```csharp
public void PrepareSearchFavorites(string filter)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | filter |   |

#### SearchFollowedFromInput
```csharp
public void SearchFollowedFromInput()
```

#### SearchFollowed
```csharp
public void SearchFollowed(string filter)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | filter |   |

#### PrepareSearchFollowed
```csharp
public void PrepareSearchFollowed(string filter)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `string` | filter |   |

#### ExeuctePreparedSearch
```csharp
public void ExeuctePreparedSearch()
```

#### SetNextSearchPage
```csharp
public void SetNextSearchPage()
```

#### SetPreviousSearchPage
```csharp
public void SetPreviousSearchPage()
```

#### SetSearchPage
```csharp
public void SetSearchPage(uint page)
```
##### Arguments
| Type | Name | Description |
| --- | --- | --- |
| `uint` | page |   |

*Generated with* [*ModularDoc*](https://github.com/hailstorm75/ModularDoc)
