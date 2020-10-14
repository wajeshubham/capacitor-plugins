# @capacitor/text-zoom

The Text Zoom API provides the ability to change Web View text size for visual accessibility.

<!--DOCGEN_INDEX_START-->
<div class="docgen docgen-index">

* [`get()`](#get)
* [`getPreferred()`](#getpreferred)
* [`set(...)`](#set)
* [Interfaces](#interfaces)

</div>
<!--DOCGEN_INDEX_END-->

<!--DOCGEN_API_START-->
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->
<div class="docgen docgen-api">

## API

### get()

```typescript
get() => Promise<GetResponse>
```

Get the current zoom level.

Zoom levels are represented as a decimal (e.g. 1.2 is 120%).

**Returns:** <code>Promise&lt;<a href="#getresponse">GetResponse</a>&gt;</code>

**Since:** 1.0.0

--------------------


### getPreferred()

```typescript
getPreferred() => Promise<GetPreferredResponse>
```

Get the preferred zoom level.

Zoom levels are represented as a decimal (e.g. 1.2 is 120%).

**Returns:** <code>Promise&lt;<a href="#getpreferredresponse">GetPreferredResponse</a>&gt;</code>

**Since:** 1.0.0

--------------------


### set(...)

```typescript
set(options: SetOptions) => Promise<void>
```

Set the current zoom level.

Zoom levels are represented as a decimal (e.g. 1.2 is 120%).

| Param         | Type                                              |
| ------------- | ------------------------------------------------- |
| **`options`** | <code><a href="#setoptions">SetOptions</a></code> |

**Returns:** <code>Promise&lt;void&gt;</code>

**Since:** 1.0.0

--------------------


### Interfaces


#### GetResponse

| Prop        | Type                | Description                                        | Since |
| ----------- | ------------------- | -------------------------------------------------- | ----- |
| **`value`** | <code>number</code> | The current zoom level (represented as a decimal). | 1.0.0 |


#### GetPreferredResponse

| Prop        | Type                | Description                                          | Since |
| ----------- | ------------------- | ---------------------------------------------------- | ----- |
| **`value`** | <code>number</code> | The preferred zoom level (represented as a decimal). | 1.0.0 |


#### SetOptions

| Prop        | Type                | Description                                    | Since |
| ----------- | ------------------- | ---------------------------------------------- | ----- |
| **`value`** | <code>number</code> | The new zoom level (represented as a decimal). | 1.0.0 |

</div>
<!--DOCGEN_API_END-->