---
id: version-2.3.0-react-native.container
title: Container class
hide_title: true
original_id: react-native.container
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->


## Container class

Skygear APIs container.

<b>Signature:</b>

```typescript
export declare class Container<T extends BaseAPIClient> 
```

## Remarks

This is the base class to Skygear APIs. Consumers should use platform-specific containers instead.

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(options)](./react-native.container._constructor_.md) |  | Constructs a new instance of the <code>Container</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [apiClient](./react-native.container.apiclient.md) |  | <code>T</code> |  |
|  [classicAuth](./react-native.container.classicauth.md) |  | <code>AuthContainer&lt;T&gt;</code> |  |
|  [name](./react-native.container.name.md) |  | <code>string</code> | Unique ID for this container. |
|  [storage](./react-native.container.storage.md) |  | <code>ContainerStorage</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [\_configure(options)](./react-native.container._configure.md) |  |  |
|  [fetch(input, init)](./react-native.container.fetch.md) |  | <code>fetch</code> function for calling microservices. |
