---
title: PewterAPIProvider - Pewter
---

[Pewter](../../index.html) / [com.ejektaflex.pewter.api](../index.html) / [PewterAPIProvider](./index.html)

# PewterAPIProvider

`open class PewterAPIProvider : `[`IPewterAPI`](../-i-pewter-a-p-i/index.html)

[PewterAPIProvider](./index.html) is a wrapper around an empty instance of the Pewter API.
At the time of mod construction, it gets replaced by Pewter's internal API
implementation.

### Constructors

| [&lt;init&gt;](-init-.html) | `PewterAPIProvider()`<br>[PewterAPIProvider](./index.html) is a wrapper around an empty instance of the Pewter API. At the time of mod construction, it gets replaced by Pewter's internal API implementation. |

### Companion Object Properties

| [api](api.html) | `var api: `[`IPewterAPI`](../-i-pewter-a-p-i/index.html) |

### Companion Object Functions

| [changeAPI](change-a-p-i.html) | `fun changeAPI(newAPI: `[`IPewterAPI`](../-i-pewter-a-p-i/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Used to change the PewterAPI implementation. |

### Inheritors

| [PewterAPI](../-pewter-a-p-i.html) | `object PewterAPI : `[`PewterAPIProvider`](./index.html)<br>The primary API object. It inherits all methods from [IPewterAPI](../-i-pewter-a-p-i/index.html). All calls to the API should be done on this object. |

