# Object - Plan Security Repurchase Release Transaction Schema

```txt
Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json
```

Object describing a plan security repurchase release transaction (when the right to repurchase is removed)

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                                                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [PlanSecurityRepurchaseRelease.schema.json](../../schema/objects/transactions/repurchaserelease/PlanSecurityRepurchaseRelease.schema.json "open original schema") |

## Object - Plan Security Repurchase Release Transaction Type

`object` ([Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease.md))

all of

*   all of

    *   all of

        *   [Object - BaseObject](issuer-allof-object---baseobject.md "check type definition")

# Object - Plan Security Repurchase Release Transaction Properties

| Property                                    | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                  |
| :------------------------------------------ | :------------ | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [object_type](#object_type)                 | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-object_type.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/object_type")                 |
| [id](#id)                                   | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-id.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/id")                                   |
| [comments](#comments)                       | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-comments.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/comments")                       |
| [security_id](#security_id)                 | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-security_id.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/security_id")                 |
| [date](#date)                               | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-date.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/date")                               |
| [settlement_date](#settlement_date)         | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-settlement_date.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/settlement_date")         |
| [release_price](#release_price)             | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-release_price.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/release_price")             |
| [net_quantity](#net_quantity)               | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-net_quantity.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/net_quantity")               |
| [method](#method)                           | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-method.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/method")                           |
| [stock_swap](#stock_swap)                   | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-stock_swap.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/stock_swap")                   |
| [cash_paid](#cash_paid)                     | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-cash_paid.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/cash_paid")                     |
| [quantity_sold](#quantity_sold)             | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-quantity_sold.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/quantity_sold")             |
| [sale_price_per_unit](#sale_price_per_unit) | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-sale_price_per_unit.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/sale_price_per_unit") |
| [withheld_quantity](#withheld_quantity)     | Not specified | Optional | cannot be null | [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-withheld_quantity.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/withheld_quantity")     |

## object_type



`object_type`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-object_type.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/object_type")

### object_type Type

unknown

### object_type Constraints

**constant**: the value of this property must be equal to:

```json
"TX_PLAN_SECURITY_REPURCHASE_RELEASE"
```

## id



`id`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-id.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/id")

### id Type

unknown

## comments



`comments`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-comments.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/comments")

### comments Type

unknown

## security_id



`security_id`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-security_id.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/security_id")

### security_id Type

unknown

## date



`date`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-date.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/date")

### date Type

unknown

## settlement_date



`settlement_date`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-settlement_date.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/settlement_date")

### settlement_date Type

unknown

## release_price



`release_price`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-release_price.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/release_price")

### release_price Type

unknown

## net_quantity



`net_quantity`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-net_quantity.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/net_quantity")

### net_quantity Type

unknown

## method



`method`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-method.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/method")

### method Type

unknown

## stock_swap



`stock_swap`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-stock_swap.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/stock_swap")

### stock_swap Type

unknown

## cash_paid



`cash_paid`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-cash_paid.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/cash_paid")

### cash_paid Type

unknown

## quantity_sold



`quantity_sold`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-quantity_sold.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/quantity_sold")

### quantity_sold Type

unknown

## sale_price_per_unit



`sale_price_per_unit`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-sale_price_per_unit.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/sale_price_per_unit")

### sale_price_per_unit Type

unknown

## withheld_quantity



`withheld_quantity`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - Plan Security Repurchase Release Transaction](plansecurityrepurchaserelease-properties-withheld_quantity.md "Objects.Transactions.RepurchaseRelease.PlanSecurityRepurchaseRelease.schema.json#/properties/withheld_quantity")

### withheld_quantity Type

unknown