# Untitled string in Root metadata for describing an identifier Schema

```txt
https://w3id.org/resolver/root.metadata.json#/properties/t_modified
```

Time at which identifier metadat was last modified. If not specified, then equal to t\_created.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                           |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [naan.schema.json\*](schema/naan.schema.json "open original schema") |

## t\_modified Type

`string`

## t\_modified Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
