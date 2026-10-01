# Untitled object in configure-module input Schema

```txt
http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [configure-module-input.json\*](hermes-agent/configure-module-input.json "open original schema") |

## items Type

`object` ([Details](configure-module-input-properties-agents-items.md))

# items Properties

| Property                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                   |
| :---------------------------- | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                     | `integer` | Required | cannot be null | [configure-module input](configure-module-input-properties-agents-items-properties-id.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/id")                     |
| [name](#name)                 | `string`  | Required | cannot be null | [configure-module input](configure-module-input-properties-agents-items-properties-name.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/name")                 |
| [role](#role)                 | `string`  | Required | cannot be null | [configure-module input](configure-module-input-properties-agents-items-properties-role.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/role")                 |
| [status](#status)             | `string`  | Required | cannot be null | [configure-module input](configure-module-input-properties-agents-items-properties-status.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/status")             |
| [allowed_user](#allowed_user) | `string`  | Optional | cannot be null | [configure-module input](configure-module-input-properties-agents-items-properties-allowed_user.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/allowed_user") |

## id



`id`

* is required

* Type: `integer`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-agents-items-properties-id.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/id")

### id Type

`integer`

### id Constraints

**maximum**: the value of this number must smaller than or equal to: `30`

**minimum**: the value of this number must greater than or equal to: `1`

## name



`name`

* is required

* Type: `string`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-agents-items-properties-name.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/name")

### name Type

`string`

### name Constraints

**minimum length**: the minimum number of characters for this string is: `1`

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z ]+$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z%20%5D%2B%24 "try regular expression with regexr.com")

## role



`role`

* is required

* Type: `string`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-agents-items-properties-role.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/role")

### role Type

`string`

### role Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                    | Explanation |
| :----------------------- | :---------- |
| `"default"`              |             |
| `"developer"`            |             |
| `"marketing"`            |             |
| `"sales"`                |             |
| `"customer_support"`     |             |
| `"social_media_manager"` |             |
| `"business_consultant"`  |             |
| `"researcher"`           |             |

## status



`status`

* is required

* Type: `string`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-agents-items-properties-status.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/status")

### status Type

`string`

### status Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"start"` |             |
| `"stop"`  |             |

## allowed_user

Bare username from the selected NS8 user domain that is allowed to access this agent dashboard when shared dashboard publishing is enabled.

`allowed_user`

* is optional

* Type: `string`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-agents-items-properties-allowed_user.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/allowed_user")

### allowed_user Type

`string`
