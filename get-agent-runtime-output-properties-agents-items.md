# Untitled object in get-agent-runtime output Schema

```txt
http://schema.nethserver.org/hermes-agent/get-agent-runtime-output.json#/properties/agents/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [get-agent-runtime-output.json\*](hermes-agent/get-agent-runtime-output.json "open original schema") |

## items Type

`object` ([Details](get-agent-runtime-output-properties-agents-items.md))

# items Properties

| Property                          | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                             |
| :-------------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [id](#id)                         | `integer` | Required | cannot be null | [get-agent-runtime output](get-agent-runtime-output-properties-agents-items-properties-id.md "http://schema.nethserver.org/hermes-agent/get-agent-runtime-output.json#/properties/agents/items/properties/id")                         |
| [runtime_status](#runtime_status) | `string`  | Required | cannot be null | [get-agent-runtime output](get-agent-runtime-output-properties-agents-items-properties-runtime_status.md "http://schema.nethserver.org/hermes-agent/get-agent-runtime-output.json#/properties/agents/items/properties/runtime_status") |

## id



`id`

* is required

* Type: `integer`

* cannot be null

* defined in: [get-agent-runtime output](get-agent-runtime-output-properties-agents-items-properties-id.md "http://schema.nethserver.org/hermes-agent/get-agent-runtime-output.json#/properties/agents/items/properties/id")

### id Type

`integer`

### id Constraints

**maximum**: the value of this number must smaller than or equal to: `30`

**minimum**: the value of this number must greater than or equal to: `1`

## runtime_status



`runtime_status`

* is required

* Type: `string`

* cannot be null

* defined in: [get-agent-runtime output](get-agent-runtime-output-properties-agents-items-properties-runtime_status.md "http://schema.nethserver.org/hermes-agent/get-agent-runtime-output.json#/properties/agents/items/properties/runtime_status")

### runtime_status Type

`string`

### runtime_status Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"start"` |             |
| `"stop"`  |             |
