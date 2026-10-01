# get-configuration output Schema

```txt
http://schema.nethserver.org/hermes-agent/get-configuration-output.json
```

Get hermes-agent configuration

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [get-configuration-output.json](hermes-agent/get-configuration-output.json "open original schema") |

## get-configuration output Type

`object` ([get-configuration output](get-configuration-output.md))

# get-configuration output Properties

| Property                              | Type      | Required | Nullable       | Defined by                                                                                                                                                                                 |
| :------------------------------------ | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [roles](#roles)                       | `array`   | Required | cannot be null | [get-configuration output](get-configuration-output-properties-roles.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/roles")                       |
| [max_agents](#max_agents)             | `integer` | Required | cannot be null | [get-configuration output](get-configuration-output-properties-max_agents.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/max_agents")             |
| [invalid_agents](#invalid_agents)     | `array`   | Required | cannot be null | [get-configuration output](get-configuration-output-properties-invalid_agents.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/invalid_agents")     |
| [base_virtualhost](#base_virtualhost) | `string`  | Required | cannot be null | [get-configuration output](get-configuration-output-properties-base_virtualhost.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/base_virtualhost") |
| [user_domain](#user_domain)           | `string`  | Required | cannot be null | [get-configuration output](get-configuration-output-properties-user_domain.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/user_domain")           |
| [lets_encrypt](#lets_encrypt)         | `boolean` | Required | cannot be null | [get-configuration output](get-configuration-output-properties-lets_encrypt.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/lets_encrypt")         |
| [agents](#agents)                     | `array`   | Required | cannot be null | [get-configuration output](get-configuration-output-properties-agents.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/agents")                     |

## roles

Roles accepted by configure-module, in display order.

`roles`

* is required

* Type: `string[]`

* cannot be null

* defined in: [get-configuration output](get-configuration-output-properties-roles.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/roles")

### roles Type

`string[]`

### roles Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

## max_agents

Highest agent id accepted by configure-module.

`max_agents`

* is required

* Type: `integer`

* cannot be null

* defined in: [get-configuration output](get-configuration-output-properties-max_agents.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/max_agents")

### max_agents Type

`integer`

### max_agents Constraints

**constant**: the value of this property must be equal to:

```json
30
```

## invalid_agents

Agent state directories whose metadata.json could not be validated. configure-module refuses to run until they are repaired or removed.

`invalid_agents`

* is required

* Type: `object[]` ([Details](get-configuration-output-properties-invalid_agents-items.md))

* cannot be null

* defined in: [get-configuration output](get-configuration-output-properties-invalid_agents.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/invalid_agents")

### invalid_agents Type

`object[]` ([Details](get-configuration-output-properties-invalid_agents-items.md))

## base_virtualhost



`base_virtualhost`

* is required

* Type: `string`

* cannot be null

* defined in: [get-configuration output](get-configuration-output-properties-base_virtualhost.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/base_virtualhost")

### base_virtualhost Type

`string`

## user_domain



`user_domain`

* is required

* Type: `string`

* cannot be null

* defined in: [get-configuration output](get-configuration-output-properties-user_domain.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/user_domain")

### user_domain Type

`string`

## lets_encrypt



`lets_encrypt`

* is required

* Type: `boolean`

* cannot be null

* defined in: [get-configuration output](get-configuration-output-properties-lets_encrypt.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/lets_encrypt")

### lets_encrypt Type

`boolean`

## agents



`agents`

* is required

* Type: `object[]` ([Details](get-configuration-output-properties-agents-items.md))

* cannot be null

* defined in: [get-configuration output](get-configuration-output-properties-agents.md "http://schema.nethserver.org/hermes-agent/get-configuration-output.json#/properties/agents")

### agents Type

`object[]` ([Details](get-configuration-output-properties-agents-items.md))
