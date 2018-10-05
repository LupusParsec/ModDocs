---
title: IPewterAPI - Pewter
---

[Pewter](../../index.html) / [com.ejektaflex.pewter.api](../index.html) / [IPewterAPI](./index.html)

# IPewterAPI

`interface IPewterAPI`

The Pewter API interface. All methods seen here are used by the API.

### Functions

| [addArmorModifier](add-armor-modifier.html) | `open fun addArmorModifier(mod: `[`EffectWrapper`](../../com.ejektaflex.pewter.api.core/-effect-wrapper/index.html)`<out `[`IPewterArmorModifier`](../../com.ejektaflex.pewter.api.core.modifiers/-i-pewter-armor-modifier.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds an armor modifier to Pewter. |
| [addArmorRepository](add-armor-repository.html) | `open fun addArmorRepository(location: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds a book repository location from which it can display modifiers in the book "Materials &amp; You: Armory Addendum", if it is loaded. |
| [addArmorTrait](add-armor-trait.html) | `open fun addArmorTrait(mod: `[`EffectWrapper`](../../com.ejektaflex.pewter.api.core/-effect-wrapper/index.html)`<out `[`IPewterTrait`](../../com.ejektaflex.pewter.api.core.traits/-i-pewter-trait.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds an armor trait to Pewter. |
| [addMaterial](add-material.html) | `open fun addMaterial(material: `[`MaterialDSL`](../../com.ejektaflex.pewter.api.core.materials/-material-d-s-l/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds a material definition to Pewter. |
| [addToolModifier](add-tool-modifier.html) | `open fun addToolModifier(mod: `[`EffectWrapper`](../../com.ejektaflex.pewter.api.core/-effect-wrapper/index.html)`<out `[`IPewterToolModifier`](../../com.ejektaflex.pewter.api.core.modifiers/-i-pewter-tool-modifier.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds a tool modifier to Pewter. |
| [addToolRepository](add-tool-repository.html) | `open fun addToolRepository(location: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds a book repository location from which it can display modifiers in the book "Materials &amp; You" |
| [addToolTrait](add-tool-trait.html) | `open fun addToolTrait(mod: `[`EffectWrapper`](../../com.ejektaflex.pewter.api.core/-effect-wrapper/index.html)`<out `[`IPewterTrait`](../../com.ejektaflex.pewter.api.core.traits/-i-pewter-trait.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds a tool trait to Pewter. |
| [log](log.html) | `open fun log(any: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Used to log API work done by Pewter. |
| [registerModule](register-module.html) | `open fun registerModule(module: `[`PewterModule`](../../com.ejektaflex.pewter.api.core/-pewter-module/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds a content module (a predefined set of materials, modifiers and traits) to Pewter. |

### Inheritors

| [PewterAPIProvider](../-pewter-a-p-i-provider/index.html) | `open class PewterAPIProvider : `[`IPewterAPI`](./index.html)<br>[PewterAPIProvider](../-pewter-a-p-i-provider/index.html) is a wrapper around an empty instance of the Pewter API. At the time of mod construction, it gets replaced by Pewter's internal API implementation. |

