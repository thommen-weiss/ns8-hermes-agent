# get-agent-runtime output Schema

```txt
http://schema.nethserver.org/hermes-agent/get-agent-runtime-output.json
```

Get Hermes agent runtime state

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [get-agent-runtime-output.json](hermes-agent/get-agent-runtime-output.json "open original schema") |

## get-agent-runtime output Type

`object` ([get-agent-runtime output](get-agent-runtime-output.md))

# get-agent-runtime output Properties

| Property          | Type    | Required | Nullable       | Defined by                                                                                                                                                             |
| :---------------- | :------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [agents](#agents) | `array` | Required | cannot be null | [get-agent-runtime output](get-agent-runtime-output-properties-agents.md "http://schema.nethserver.org/hermes-agent/get-agent-runtime-output.json#/properties/agents") |

## agents



`agents`

* is required

* Type: `object[]` ([Details](get-agent-runtime-output-properties-agents-items.md))

* cannot be null

* defined in: [get-agent-runtime output](get-agent-runtime-output-properties-agents.md "http://schema.nethserver.org/hermes-agent/get-agent-runtime-output.json#/properties/agents")

### agents Type

`object[]` ([Details](get-agent-runtime-output-properties-agents-items.md))
