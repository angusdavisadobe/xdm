
# Profile Counters Mixin Extension Schema

```
https://ns.adobe.com/experience/customerJourneyManagement/profile-counters
```

Holds a map of objects containing counter_value and counter_expiry, keyed by counter_id.

| [Abstract](../../../../abstract.md) | [Extensible](../../../../extensions.md) | [Status](../../../../status.md) | [Identifiable](../../../../id.md) | [Custom Properties](../../../../extensions.md) | [Additional Properties](../../../../extensions.md) | Defined In |
|-------------------------------------|-----------------------------------------|---------------------------------|-----------------------------------|------------------------------------------------|----------------------------------------------------|------------|
| Can be instantiated | Yes | Stable | No | Forbidden | Permitted | [adobe/experience/customerJourneyManagement/profile-counters.schema.json](adobe/experience/customerJourneyManagement/profile-counters.schema.json) |

## Profile Counters Mixin Extension Examples

```json
{
  "xdm:namespace": {
    "xdm:code": "ECID"
  },
  "xdm:id": "92312748749128",
  "xdm:frequencyMap": {
    "counter_id": {
      "xdm:value": 100,
      "xdm:expiry": 1828377772381
    }
  }
}
```

```json
{
  "xdm:xid": "xid-92312748749128",
  "xdm:frequencyMap": {
    "counter_id": {
      "xdm:value": 100,
      "xdm:expiry": 1828377772381
    }
  }
}
```


# Profile Counters Mixin Extension Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [xdm:frequencyMap](#xdmfrequencymap) | `object` | Optional | Profile Counters Mixin Extension (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## xdm:frequencyMap

A map from counter_id to objects containing counter_value, counter_expiry

`xdm:frequencyMap`
* is optional
* type: `object`
* defined in this schema

### xdm:frequencyMap Type


`object` with following properties:


| Property | Type | Required |
|----------|------|----------|





