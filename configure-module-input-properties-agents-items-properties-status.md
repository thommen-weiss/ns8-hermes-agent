# Untitled string in configure-module input Schema

```txt
http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/status
```



| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [configure-module-input.json\*](hermes-agent/configure-module-input.json "open original schema") |

## status Type

`string`

## status Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value     | Explanation |
| :-------- | :---------- |
| `"start"` |             |
| `"stop"`  |             |
