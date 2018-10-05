---
title: com.ejektaflex.pewter.api - Pewter
---

[Pewter](../index.html) / [com.ejektaflex.pewter.api](./index.html)

## Package com.ejektaflex.pewter.api

### Types

| [IPewterAPI](-i-pewter-a-p-i/index.html) | `interface IPewterAPI`<br>The Pewter API interface. All methods seen here are used by the API. |
| [PewterAPI](-pewter-a-p-i.html) | `object PewterAPI : `[`PewterAPIProvider`](-pewter-a-p-i-provider/index.html)<br>The primary API object. It inherits all methods from [IPewterAPI](-i-pewter-a-p-i/index.html). All calls to the API should be done on this object. |
| [PewterAPIProvider](-pewter-a-p-i-provider/index.html) | `open class PewterAPIProvider : `[`IPewterAPI`](-i-pewter-a-p-i/index.html)<br>[PewterAPIProvider](-pewter-a-p-i-provider/index.html) is a wrapper around an empty instance of the Pewter API. At the time of mod construction, it gets replaced by Pewter's internal API implementation. |

