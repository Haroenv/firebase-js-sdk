<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [lite](./firestore_lite.md) &gt; [collection](./firestore_lite.collection.md)

## collection() function

Gets a `CollectionReference` instance that refers to the collection at the specified absolute path.

<b>Signature:</b>

```typescript
export declare function collection(firestore: FirebaseFirestore, path: string, ...pathSegments: string[]): CollectionReference<DocumentData>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  firestore | [FirebaseFirestore](./firestore_lite.firebasefirestore.md) | A reference to the root Firestore instance. |
|  path | string | A slash-separated path to a collection. |
|  pathSegments | string\[\] | Additional path segments to apply relative to the first argument. |

<b>Returns:</b>

[CollectionReference](./firestore_lite.collectionreference.md)<!-- -->&lt;[DocumentData](./firestore_lite.documentdata.md)<!-- -->&gt;

The `CollectionReference` instance.

## Exceptions

If the final path has an even number of segments and does not point to a collection.
