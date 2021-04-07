<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth-types](./auth-types.md) &gt; [ParsedToken](./auth-types.parsedtoken.md)

## ParsedToken interface

Interface representing a parsed ID token.

<b>Signature:</b>

```typescript
export interface ParsedToken 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [auth\_time](./auth-types.parsedtoken.auth_time.md) | string | Time at which authentication was performed. |
|  [exp](./auth-types.parsedtoken.exp.md) | string | Expiration time of the token. |
|  [firebase](./auth-types.parsedtoken.firebase.md) | { 'sign\_in\_provider'?: string; 'sign\_in\_second\_factor'?: string; } | Firebase specific claims, containing the provider(s) used to authenticate the user. |
|  [iat](./auth-types.parsedtoken.iat.md) | string | Issuance time of the token. |
|  [sub](./auth-types.parsedtoken.sub.md) | string | UID of the user. |
