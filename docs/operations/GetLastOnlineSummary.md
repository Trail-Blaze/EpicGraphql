# GetLastOnlineSummary

Description here, manual action needed.

## Request
| URL | METHOD |
| - | - |
| https://graphql.epicgames.com/partyhub/graphql | POST |

## Query
```
query GetLastOnlineSummary($namespace: String!) { PresenceV2 { __typename getLastOnlineSummary(namespace: $namespace, circle: "friends") { __typename summary { __typename friendId namespace circle last_online } } } }
```

## Variables
```json
{
   "namespace": ""
}
```
| VARIABLES | DESCRIPTION | TYPE |
| - | - | - |
| namespace | The short/full name of the game. | String |

## Payload
```json
{
   "operationName": "GetLastOnlineSummary",
   "variables": {},
   "query": "query GetLastOnlineSummary($namespace: String!) { PresenceV2 { __typename getLastOnlineSummary(namespace: $namespace, circle: \"friends\") { __typename summary { __typename friendId namespace circle last_online } } } }"
}
```