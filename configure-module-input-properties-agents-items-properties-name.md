# Untitled string in configure-module input Schema

```txt
http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents/items/properties/name
```



| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [configure-module-input.json\*](hermes-agent/configure-module-input.json "open original schema") |

## name Type

`string`

## name Constraints

**minimum length**: the minimum number of characters for this string is: `1`

**pattern**: the string must match the following regular expression:&#x20;

```regexp
^[A-Za-z ]+$
```

[try pattern](https://regexr.com/?expression=%5E%5BA-Za-z%20%5D%2B%24 "try regular expression with regexr.com")
