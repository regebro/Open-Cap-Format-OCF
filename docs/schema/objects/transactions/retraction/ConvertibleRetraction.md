:house: [Documentation Home](/README.md)

---

### Object - Convertible Retraction Transaction

`https://opencaptablecoalition.com/schema/objects/transactions/retraction/ConvertibleRetraction.schema.json`

**Description:** _Object describing a retraction of a convertible security_

**Data Type:** `OCF Object - TX_CONVERTIBLE_RETRACTION`

**Composed From:**

- [schema/primitives/BaseObject](/docs/schema/primitives/BaseObject.md)
- [schema/primitives/transactions/BaseTransaction](/docs/schema/primitives/transactions/BaseTransaction.md)
- [schema/primitives/transactions/retraction/BaseRetraction](/docs/schema/primitives/transactions/retraction/BaseRetraction.md)

**Properties:**

| Property    | Type                                                                                                                   | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Required   |
| ----------- | ---------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| id          | `STRING`                                                                                                               | Identifier for the object                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | `REQUIRED` |
| comments    | [`STRING`]                                                                                                             | Unstructured text comments related to and stored for the object                                                                                                                                                                                                                                                                                                                                                                                                                                             | -          |
| object_type | **Constant:** `TX_CONVERTIBLE_RETRACTION`</br>_Defined in [schema/enums/ObjectType](/docs/schema/enums/ObjectType.md)_ | Object type field                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | `REQUIRED` |
| security_id | `STRING`                                                                                                               | Identifier for the security (stock, plan security, warrant, or convertible) by which it can be referenced by other transaction objects. Note that while this identifier is created with an issuance object, it should be different than the issuance object's `id` field which identifies the issuance transaction object itself. All future transactions on the security (e.g. acceptance, transfer, cancel, etc.) must reference this `security_id` to qualify which security the transaction applies to. | `REQUIRED` |
| date        | [schema/types/Date](/docs/schema/types/Date.md)                                                                        | Date on which the transaction occurred                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | `REQUIRED` |
| reason_text | `STRING`                                                                                                               | Reason for the retraction                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | `REQUIRED` |

**Source Code:** [schema/objects/transactions/retraction/ConvertibleRetraction](/schema/objects/transactions/retraction/ConvertibleRetraction.schema.json)

**Examples:**

```json
[
  {
    "object_type": "TX_CONVERTIBLE_RETRACTION",
    "id": "test-convertible-retraction-minimal",
    "security_id": "test-convertible-retraction",
    "date": "2021-01-14",
    "reason_text": "oops"
  },
  {
    "object_type": "TX_CONVERTIBLE_RETRACTION",
    "id": "test-convertible-retraction-all-fields",
    "security_id": "test-convertible-retraction",
    "date": "2021-01-14",
    "reason_text": "oops",
    "comments": [
      "comment-one",
      "comment-two",
      "..."
    ]
  }
]
```