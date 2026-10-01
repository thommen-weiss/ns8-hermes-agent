# Untitled object in list-domain-users output Schema

```txt
http://schema.nethserver.org/hermes-agent/list-domain-users-output.json#/properties/users/items
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                           |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [list-domain-users-output.json\*](hermes-agent/list-domain-users-output.json "open original schema") |

## items Type

`object` ([Details](list-domain-users-output-properties-users-items.md))

# items Properties

| Property                      | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                       |
| :---------------------------- | :-------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [user](#user)                 | `string`  | Required | cannot be null | [list-domain-users output](list-domain-users-output-properties-users-items-properties-user.md "http://schema.nethserver.org/hermes-agent/list-domain-users-output.json#/properties/users/items/properties/user")                 |
| [display_name](#display_name) | Multiple  | Optional | cannot be null | [list-domain-users output](list-domain-users-output-properties-users-items-properties-display_name.md "http://schema.nethserver.org/hermes-agent/list-domain-users-output.json#/properties/users/items/properties/display_name") |
| [locked](#locked)             | `boolean` | Optional | cannot be null | [list-domain-users output](list-domain-users-output-properties-users-items-properties-locked.md "http://schema.nethserver.org/hermes-agent/list-domain-users-output.json#/properties/users/items/properties/locked")             |
| [mail](#mail)                 | Multiple  | Optional | cannot be null | [list-domain-users output](list-domain-users-output-properties-users-items-properties-mail.md "http://schema.nethserver.org/hermes-agent/list-domain-users-output.json#/properties/users/items/properties/mail")                 |
| Additional Properties         | Any       | Optional | can be null    |                                                                                                                                                                                                                                  |

## user



`user`

* is required

* Type: `string`

* cannot be null

* defined in: [list-domain-users output](list-domain-users-output-properties-users-items-properties-user.md "http://schema.nethserver.org/hermes-agent/list-domain-users-output.json#/properties/users/items/properties/user")

### user Type

`string`

## display_name



`display_name`

* is optional

* Type: any of the following: `string` or `array` ([Details](list-domain-users-output-properties-users-items-properties-display_name.md))

* cannot be null

* defined in: [list-domain-users output](list-domain-users-output-properties-users-items-properties-display_name.md "http://schema.nethserver.org/hermes-agent/list-domain-users-output.json#/properties/users/items/properties/display_name")

### display_name Type

any of the following: `string` or `array` ([Details](list-domain-users-output-properties-users-items-properties-display_name.md))

## locked



`locked`

* is optional

* Type: `boolean`

* cannot be null

* defined in: [list-domain-users output](list-domain-users-output-properties-users-items-properties-locked.md "http://schema.nethserver.org/hermes-agent/list-domain-users-output.json#/properties/users/items/properties/locked")

### locked Type

`boolean`

## mail



`mail`

* is optional

* Type: any of the following: `string` or `array` ([Details](list-domain-users-output-properties-users-items-properties-mail.md))

* cannot be null

* defined in: [list-domain-users output](list-domain-users-output-properties-users-items-properties-mail.md "http://schema.nethserver.org/hermes-agent/list-domain-users-output.json#/properties/users/items/properties/mail")

### mail Type

any of the following: `string` or `array` ([Details](list-domain-users-output-properties-users-items-properties-mail.md))

## Additional Properties

Additional properties are allowed and do not have to follow a specific schema
