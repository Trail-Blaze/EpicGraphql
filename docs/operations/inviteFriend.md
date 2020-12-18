# inviteFriend

Description here, manual action needed.

## Request
| URL | METHOD |
| - | - |
| https://graphql.epicgames.com/partyhub/graphql | POST |

## Query
```
mutation inviteFriend($friendId: String!) { Friends { __typename invite(friendToInvite: $friendId) { __typename success } } }
```

## Variables
```json
{
   "friendId": ""
}
```
| VARIABLES | DESCRIPTION | TYPE |
| - | - | - |
| friendId | A friend ID. | STRING |

## Payload
```json
{
   "operationName": "inviteFriend",
   "variables": {},
   "query": "mutation inviteFriend($friendId: String!) { Friends { __typename invite(friendToInvite: $friendId) { __typename success } } }"
}
```