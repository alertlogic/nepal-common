<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@al/common](./common.md) &gt; [AlSubscriptionGroup](./common.alsubscriptiongroup.md)

## AlSubscriptionGroup class

This is a simple utility to manage a list of subscriptions, which may be AlTriggerSubscriptions or RxJS subscriptions. It exposes a method `manage` to add new subscriptions, and a method `cancelAll` to unsubscribe from all subscriptions. That is all it does.

<b>Signature:</b>

```typescript
export declare class AlSubscriptionGroup 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(items)](./common.alsubscriptiongroup._constructor_.md) |  | Constructs a new instance of the <code>AlSubscriptionGroup</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [subscriptions](./common.alsubscriptiongroup.subscriptions.md) |  | <code>any[]</code> |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [cancelAll()](./common.alsubscriptiongroup.cancelall.md) |  | Cancels/unsubscribes from all subscriptions. |
|  [manage(items)](./common.alsubscriptiongroup.manage.md) |  | Adds one or more subscriptions (as themselves, in arrays, via callback function, or some mixture of these inputs) to the internal list of managed items. |
