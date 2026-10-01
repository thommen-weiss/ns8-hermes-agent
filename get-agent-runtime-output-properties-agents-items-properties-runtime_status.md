# Untitled string in get-agent-runtime output Schema

```txt
http://schema.nethserver.org/hermes-agent/get-agent-runtime-output.json#/properties/agents/items/properties/runtime_status
```



| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [get-agent-runtime-output.json\*](hermes-agent/get-agent-runtime-output.json "open original schema") |

## runtime_status Type

`string`

## runtime_status Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"start"` |             |
| `"stop"`  |             |
