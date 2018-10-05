---
title: PewterModule - Pewter
---

[Pewter](../../index.html) / [com.ejektaflex.pewter.api.core](../index.html) / [PewterModule](./index.html)

# PewterModule

`abstract class PewterModule`

A [PewterModule](./index.html) is a set of materials, tools and traits.
[com.ejektaflex.pewter.api.PewterAPI.registerModule](#) will register this
module so that Pewter can load it later on.

### Constructors

| [&lt;init&gt;](-init-.html) | `PewterModule()`<br>A [PewterModule](./index.html) is a set of materials, tools and traits. [com.ejektaflex.pewter.api.PewterAPI.registerModule](#) will register this module so that Pewter can load it later on. |

### Properties

| [armorModifiers](armor-modifiers.html) | `open val armorModifiers: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`EffectWrapper`](../-effect-wrapper/index.html)`<out `[`IPewterArmorModifier`](../../com.ejektaflex.pewter.api.core.modifiers/-i-pewter-armor-modifier.html)`>>` |
| [armorTraits](armor-traits.html) | `open val armorTraits: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`EffectWrapper`](../-effect-wrapper/index.html)`<out `[`IPewterArmorTrait`](../../com.ejektaflex.pewter.api.core.traits/-i-pewter-armor-trait.html)`>>` |
| [id](id.html) | `abstract val id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>A unique identifier for the module. May be used in the future to query the API for modules; Currently unused. |
| [materials](materials.html) | `open val materials: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`MaterialDSL`](../../com.ejektaflex.pewter.api.core.materials/-material-d-s-l/index.html)`>` |
| [toolModifiers](tool-modifiers.html) | `open val toolModifiers: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`EffectWrapper`](../-effect-wrapper/index.html)`<out `[`IPewterToolModifier`](../../com.ejektaflex.pewter.api.core.modifiers/-i-pewter-tool-modifier.html)`>>` |
| [toolTraits](tool-traits.html) | `open val toolTraits: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`EffectWrapper`](../-effect-wrapper/index.html)`<out `[`IPewterToolTrait`](../../com.ejektaflex.pewter.api.core.traits/-i-pewter-tool-trait.html)`>>` |

### Functions

| [hasMetDependencies](has-met-dependencies.html) | `open fun hasMetDependencies(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Here you can define the conditions that determine whether or not the module should load. By default, it checks whether there is a mod with the same ID as the module ID to determine whether it should load. |

