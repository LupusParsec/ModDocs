[Pewter](../index.md) / [com.ejektaflex.pewter.api](./index.md)

## Package com.ejektaflex.pewter.api

### Types

| Name | Summary |
|---|---|
| [IPewterAPI](-i-pewter-a-p-i/index.md) | `interface IPewterAPI`<br>The Pewter API interface. All methods seen here are used by the API. |
| [PewterAPI](-pewter-a-p-i.md) | `object PewterAPI : `[`PewterAPIProvider`](-pewter-a-p-i-provider/index.md)<br>The primary API object. It inherits all methods from [IPewterAPI](-i-pewter-a-p-i/index.md). All calls to the API should be done on this object. |
| [PewterAPIProvider](-pewter-a-p-i-provider/index.md) | `open class PewterAPIProvider : `[`IPewterAPI`](-i-pewter-a-p-i/index.md)<br>[PewterAPIProvider](-pewter-a-p-i-provider/index.md) is a wrapper around an empty instance of the Pewter API. At the time of mod construction, it gets replaced by Pewter's internal API implementation. |
