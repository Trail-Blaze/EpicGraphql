# SetSubscriptionSettings

Description here, manual action needed.

## Request
| URL | METHOD |
| - | - |
| https://graphql.epicgames.com/partyhub/graphql | POST |

## Query
```
mutation SetSubscriptionSettings($setting: SubscriptionSettingsInput!) { PresenceV2 { __typename modifySubscriptionSettings(namespace: "_", value: $setting) { __typename success } } }
```

## Variables
```json
{
   "setting": {}
}
```
| VARIABLES | DESCRIPTION | TYPE |
| - | - | - |
| setting | None | object |

## Payload
```json
{
   "operationName": "SetSubscriptionSettings",
   "variables": {},
   "query": "mutation SetSubscriptionSettings($setting: SubscriptionSettingsInput!) { PresenceV2 { __typename modifySubscriptionSettings(namespace: \"_\", value: $setting) { __typename success } } }"
}
```