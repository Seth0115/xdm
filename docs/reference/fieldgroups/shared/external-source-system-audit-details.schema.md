
# External Source System Audit Details Schema

```
https://ns.adobe.com/xdm/common/external-source-system-audit-details
```

Defines a set of audit properties for extenal sources. It's strongly encouraged to use this fieldgroup given the asynchronous nature of profile ingestion.

| [Abstract](../../../abstract.md) | [Extensible](../../../extensions.md) | [Status](../../../status.md) | [Identifiable](../../../id.md) | [Custom Properties](../../../extensions.md) | [Additional Properties](../../../extensions.md) | Defined In |
|----------------------------------|--------------------------------------|------------------------------|--------------------------------|---------------------------------------------|-------------------------------------------------|------------|
| Can be instantiated | Yes | Stable | No | Forbidden | Permitted | [fieldgroups/shared/external-source-system-audit-details.schema.json](fieldgroups/shared/external-source-system-audit-details.schema.json) |
## Schema Hierarchy

* External Source System Audit Details `https://ns.adobe.com/xdm/common/external-source-system-audit-details`
  * [Extensibility base schema](../../datatypes/extensible.schema.md) `https://ns.adobe.com/xdm/common/extensible`
  * [External Source System Audit Attributes](../../datatypes/auditing/external-source-system-audit.schema.md) `https://ns.adobe.com/xdm/common/external-source-system-audit`


## External Source System Audit Details Example
```json
{
  "xdm:createdBy": "USER111",
  "xdm:createdDate": "2018-01-02T15:52:25+00:00",
  "xdm:lastUpdatedBy": "USER2222",
  "xdm:lastUpdatedDate": "2018-01-02T15:52:25+00:00",
  "xdm:lastActivityDate": "2018-01-02T15:52:25+00:00",
  "xdm:lastReferencedDate": "2018-01-02T15:52:25+00:00",
  "xdm:lastViewedDate": "2018-01-02T15:52:25+00:00"
}
```

# External Source System Audit Details Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [xdm:extSourceSystemAudit](#xdmextsourcesystemaudit) | External Source System Audit Attributes | Optional | External Source System Audit Details (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## xdm:extSourceSystemAudit
### External Source System Audit Properties

Audit attributes for external sources.

`xdm:extSourceSystemAudit`
* is optional
* type: External Source System Audit Attributes
* defined in this schema

### xdm:extSourceSystemAudit Type


* [External Source System Audit Attributes](../../datatypes/auditing/external-source-system-audit.schema.md) – `https://ns.adobe.com/xdm/common/external-source-system-audit`




