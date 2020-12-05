<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [/](./firestore_.md) &gt; [endAt](./firestore_.endat.md)

## endAt() function

Creates a `QueryConstraint` that modifies the result set to end at the provided document (inclusive). The end position is relative to the order of the query. The document must contain all of the fields provided in the orderBy of the query.

<b>Signature:</b>

```typescript
export declare function endAt(snapshot: DocumentSnapshot<unknown>): QueryConstraint;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  snapshot | [DocumentSnapshot](./firestore_.documentsnapshot.md)<!-- -->&lt;unknown&gt; | The snapshot of the document to end at. |

<b>Returns:</b>

[QueryConstraint](./firestore_.queryconstraint.md)

A `QueryConstraint` to pass to `query()`
