# configure-module input Schema

```txt
http://schema.nethserver.org/hermes-agent/configure-module-input.json
```

Configure hermes-agent

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                     |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [configure-module-input.json](hermes-agent/configure-module-input.json "open original schema") |

## configure-module input Type

`object` ([configure-module input](configure-module-input.md))

# configure-module input Properties

| Property                              | Type      | Required | Nullable       | Defined by                                                                                                                                                                           |
| :------------------------------------ | :-------- | :------- | :------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [base_virtualhost](#base_virtualhost) | Merged    | Optional | cannot be null | [configure-module input](configure-module-input-properties-base_virtualhost.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/base_virtualhost") |
| [user_domain](#user_domain)           | `string`  | Optional | cannot be null | [configure-module input](configure-module-input-properties-user_domain.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/user_domain")           |
| [lets_encrypt](#lets_encrypt)         | `boolean` | Optional | cannot be null | [configure-module input](configure-module-input-properties-lets_encrypt.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/lets_encrypt")         |
| [agents](#agents)                     | `array`   | Required | cannot be null | [configure-module input](configure-module-input-properties-agents.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents")                     |

## base_virtualhost

Base virtualhost for agent dashboards. When set, every agent gets a Traefik route at https\://<host>/hermes-N/ that forwards to its dedicated Hermes web dashboard. Must be a valid fully qualified domain name or left empty to disable shared dashboard hosting.

`base_virtualhost`

* is optional

* Type: merged type ([Details](configure-module-input-properties-base_virtualhost.md))

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-base_virtualhost.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/base_virtualhost")

### base_virtualhost Type

merged type ([Details](configure-module-input-properties-base_virtualhost.md))

any of

* [Untitled string in configure-module input](configure-module-input-properties-base_virtualhost-anyof-0.md "check type definition")

* not

  * [Untitled undefined type in configure-module input](configure-module-input-properties-base_virtualhost-anyof-1-not.md "check type definition")

## user_domain

Selected NS8 user domain used to authenticate dashboard logins when shared dashboard publishing is enabled. Leave empty to disable domain-backed dashboard authentication setup.

`user_domain`

* is optional

* Type: `string`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-user_domain.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/user_domain")

### user_domain Type

`string`

## lets_encrypt

Request a Let's Encrypt certificate for the shared dashboard virtualhost when routes are published through Traefik.

`lets_encrypt`

* is optional

* Type: `boolean`

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-lets_encrypt.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/lets_encrypt")

### lets_encrypt Type

`boolean`

## agents



`agents`

* is required

* Type: `object[]` ([Details](configure-module-input-properties-agents-items.md))

* cannot be null

* defined in: [configure-module input](configure-module-input-properties-agents.md "http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/agents")

### agents Type

`object[]` ([Details](configure-module-input-properties-agents-items.md))
