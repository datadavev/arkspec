# Root metadata for describing an identifier Schema

```txt
https://w3id.org/resolver/root.metadata.json
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                         |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [naan.schema.json](schema/naan.schema.json "open original schema") |

## Root metadata for describing an identifier Type

`object` ([Root metadata for describing an identifier](naan.md))

# Root metadata for describing an identifier Properties

| Property                   | Type     | Required | Nullable       | Defined by                                                                                                                                        |
| :------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                  | `string` | Required | cannot be null | [Root metadata for describing an identifier](naan-properties-id.md "https://w3id.org/resolver/root.metadata.json#/properties/id")                 |
| [location](#location)      | `string` | Required | cannot be null | [Root metadata for describing an identifier](naan-properties-location.md "https://w3id.org/resolver/root.metadata.json#/properties/location")     |
| [t\_created](#t_created)   | `string` | Required | cannot be null | [Root metadata for describing an identifier](naan-properties-t_created.md "https://w3id.org/resolver/root.metadata.json#/properties/t_created")   |
| [t\_modified](#t_modified) | `string` | Optional | cannot be null | [Root metadata for describing an identifier](naan-properties-t_modified.md "https://w3id.org/resolver/root.metadata.json#/properties/t_modified") |
| [type](#type)              | `string` | Optional | cannot be null | [Root metadata for describing an identifier](naan-properties-type.md "https://w3id.org/resolver/root.metadata.json#/properties/type")             |
| [creator](#creator)        | `string` | Optional | cannot be null | [Root metadata for describing an identifier](naan-properties-creator.md "https://w3id.org/resolver/root.metadata.json#/properties/creator")       |
| [about](#about)            | `object` | Optional | cannot be null | [Root metadata for describing an identifier](naan-properties-about.md "https://w3id.org/resolver/root.metadata.json#/properties/about")           |

## id

The identifier described by this document

`id`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Root metadata for describing an identifier](naan-properties-id.md "https://w3id.org/resolver/root.metadata.json#/properties/id")

### id Type

`string`

## location

Location at which identified resource may be retrieved

`location`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Root metadata for describing an identifier](naan-properties-location.md "https://w3id.org/resolver/root.metadata.json#/properties/location")

### location Type

`string`

### location Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

## t\_created

Origin time of the identifier

`t_created`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Root metadata for describing an identifier](naan-properties-t_created.md "https://w3id.org/resolver/root.metadata.json#/properties/t_created")

### t\_created Type

`string`

### t\_created Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## t\_modified

Time at which identifier metadat was last modified. If not specified, then equal to t\_created.

`t_modified`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Root metadata for describing an identifier](naan-properties-t_modified.md "https://w3id.org/resolver/root.metadata.json#/properties/t_modified")

### t\_modified Type

`string`

### t\_modified Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## type

The URI of the type definition of the identified resource

`type`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Root metadata for describing an identifier](naan-properties-type.md "https://w3id.org/resolver/root.metadata.json#/properties/type")

### type Type

`string`

### type Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

## creator

The creator of the identifier

`creator`

*   is optional

*   Type: `string`

*   cannot be null

*   defined in: [Root metadata for describing an identifier](naan-properties-creator.md "https://w3id.org/resolver/root.metadata.json#/properties/creator")

### creator Type

`string`

### creator Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc3986 "check the specification")

## about

Descriptive metadata about the identified resource.

`about`

*   is optional

*   Type: `object` ([Details](naan-properties-about.md))

*   cannot be null

*   defined in: [Root metadata for describing an identifier](naan-properties-about.md "https://w3id.org/resolver/root.metadata.json#/properties/about")

### about Type

`object` ([Details](naan-properties-about.md))
