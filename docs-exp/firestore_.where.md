<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [/](./firestore_.md) &gt; [where](./firestore_.where.md)

## where() function

Creates a `QueryConstraint` that enforces that documents must contain the specified field and that the value should satisfy the relation constraint provided.

<b>Signature:</b>

```typescript
export declare function where(fieldPath: string | FieldPath, opStr: WhereFilterOp, value: unknown): QueryConstraint;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  fieldPath | string \| [FieldPath](./firestore_.fieldpath.md) | The path to compare |
|  opStr | [WhereFilterOp](./firestore_.wherefilterop.md) | The operation string (e.g "&amp;lt;", "&amp;lt;=", "==", "&amp;lt;", "&amp;lt;=", "!="). |
|  value | unknown | The value for comparison |

<b>Returns:</b>

[QueryConstraint](./firestore_.queryconstraint.md)

The created `Query`<!-- -->.

