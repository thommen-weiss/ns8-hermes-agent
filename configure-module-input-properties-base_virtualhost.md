# Untitled undefined type in configure-module input Schema

```txt
http://schema.nethserver.org/hermes-agent/configure-module-input.json#/properties/base_virtualhost
```

Base virtualhost for agent dashboards. When set, every agent gets a Traefik route at https\://<host>/hermes-N/ that forwards to its dedicated Hermes web dashboard. Must be a valid fully qualified domain name or left empty to disable shared dashboard hosting.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                       |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [configure-module-input.json\*](hermes-agent/configure-module-input.json "open original schema") |

## base_virtualhost Type

merged type ([Details](configure-module-input-properties-base_virtualhost.md))

any of

* [Untitled string in configure-module input](configure-module-input-properties-base_virtualhost-anyof-0.md "check type definition")

* not

  * [Untitled undefined type in configure-module input](configure-module-input-properties-base_virtualhost-anyof-1-not.md "check type definition")
