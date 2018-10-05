[Pewter](../../index.md) / [com.ejektaflex.pewter.api](../index.md) / [PewterAPIProvider](./index.md)

# PewterAPIProvider

`open class PewterAPIProvider : `[`IPewterAPI`](../-i-pewter-a-p-i/index.md)

[PewterAPIProvider](./index.md) is a wrapper around an empty instance of the Pewter API.
At the time of mod construction, it gets replaced by Pewter's internal API
implementation.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PewterAPIProvider()`<br>[PewterAPIProvider](./index.md) is a wrapper around an empty instance of the Pewter API. At the time of mod construction, it gets replaced by Pewter's internal API implementation. |

### Companion Object Properties

| Name | Summary |
|---|---|
| [api](api.md) | `var api: `[`IPewterAPI`](../-i-pewter-a-p-i/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [changeAPI](change-a-p-i.md) | `fun changeAPI(newAPI: `[`IPewterAPI`](../-i-pewter-a-p-i/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Used to change the PewterAPI implementation. |

### Inheritors

| Name | Summary |
|---|---|
| [PewterAPI](../-pewter-a-p-i.md) | `object PewterAPI : `[`PewterAPIProvider`](./index.md)<br>The primary API object. It inherits all methods from [IPewterAPI](../-i-pewter-a-p-i/index.md). All calls to the API should be done on this object. |
