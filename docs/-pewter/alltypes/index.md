---
title: alltypes - Pewter
---

### All Types

| [com.ejektaflex.pewter.api.core.materials.stats.ArmorStats](../com.ejektaflex.pewter.api.core.materials.stats/-armor-stats/index.html) |  |
| [com.ejektaflex.pewter.api.core.materials.DSL](../com.ejektaflex.pewter.api.core.materials/-d-s-l/index.html) | The base class for all Material DSLs. |
| [com.ejektaflex.pewter.api.core.EffectWrapper](../com.ejektaflex.pewter.api.core/-effect-wrapper/index.html) | This is a simple wrapper around an effect that allows you to store a reference to an effect without instantiating it. This is needed because these effects get registered into registries when they're instantiated. Multiple instantiations of a tool effect will then cause an error due to how they're implemented in TiC/ConArm. |
| [com.ejektaflex.pewter.api.IPewterAPI](../com.ejektaflex.pewter.api/-i-pewter-a-p-i/index.html) | The Pewter API interface. All methods seen here are used by the API. |
| [com.ejektaflex.pewter.api.core.modifiers.IPewterArmorModifier](../com.ejektaflex.pewter.api.core.modifiers/-i-pewter-armor-modifier.html) |  |
| [com.ejektaflex.pewter.api.core.traits.IPewterArmorTrait](../com.ejektaflex.pewter.api.core.traits/-i-pewter-armor-trait.html) |  |
| [com.ejektaflex.pewter.api.core.IPewterBaseEffect](../com.ejektaflex.pewter.api.core/-i-pewter-base-effect.html) | A base interface from which all Pewter Tool/Armor Modifier/Traits come from. |
| [com.ejektaflex.pewter.api.core.modifiers.IPewterModifier](../com.ejektaflex.pewter.api.core.modifiers/-i-pewter-modifier/index.html) |  |
| [com.ejektaflex.pewter.api.core.modifiers.IPewterToolModifier](../com.ejektaflex.pewter.api.core.modifiers/-i-pewter-tool-modifier.html) |  |
| [com.ejektaflex.pewter.api.core.traits.IPewterToolTrait](../com.ejektaflex.pewter.api.core.traits/-i-pewter-tool-trait.html) |  |
| [com.ejektaflex.pewter.api.core.traits.IPewterTrait](../com.ejektaflex.pewter.api.core.traits/-i-pewter-trait.html) |  |
| [com.ejektaflex.pewter.api.core.materials.MaterialDSL](../com.ejektaflex.pewter.api.core.materials/-material-d-s-l/index.html) | A Kotlin DSL that describes a Tinkers' Construct Material. Used as a proxy for configuring materials more easily. |
| [com.ejektaflex.pewter.api.core.materials.stats.MaterialData](../com.ejektaflex.pewter.api.core.materials.stats/-material-data/index.html) |  |
| [com.ejektaflex.pewter.api.PewterAPI](../com.ejektaflex.pewter.api/-pewter-a-p-i.html) | The primary API object. It inherits all methods from [IPewterAPI](../com.ejektaflex.pewter.api/-i-pewter-a-p-i/index.html). All calls to the API should be done on this object. |
| [com.ejektaflex.pewter.api.PewterAPIProvider](../com.ejektaflex.pewter.api/-pewter-a-p-i-provider/index.html) | [PewterAPIProvider](../com.ejektaflex.pewter.api/-pewter-a-p-i-provider/index.html) is a wrapper around an empty instance of the Pewter API. At the time of mod construction, it gets replaced by Pewter's internal API implementation. |
| [com.ejektaflex.pewter.api.core.modifiers.PewterAccessory](../com.ejektaflex.pewter.api.core.modifiers/-pewter-accessory/index.html) |  |
| [com.ejektaflex.pewter.api.core.modifiers.PewterArmorModifier](../com.ejektaflex.pewter.api.core.modifiers/-pewter-armor-modifier/index.html) | Extend this if you want to create a new armor modifier. |
| [com.ejektaflex.pewter.api.core.traits.PewterArmorTrait](../com.ejektaflex.pewter.api.core.traits/-pewter-armor-trait/index.html) | Extend this if you want to create a new Armor trait. |
| [com.ejektaflex.pewter.api.core.PewterModule](../com.ejektaflex.pewter.api.core/-pewter-module/index.html) | A [PewterModule](../com.ejektaflex.pewter.api.core/-pewter-module/index.html) is a set of materials, tools and traits. [com.ejektaflex.pewter.api.PewterAPI.registerModule](#) will register this module so that Pewter can load it later on. |
| [com.ejektaflex.pewter.api.core.traits.PewterProjectileTrait](../com.ejektaflex.pewter.api.core.traits/-pewter-projectile-trait/index.html) |  |
| [com.ejektaflex.pewter.api.core.modifiers.PewterToolModifier](../com.ejektaflex.pewter.api.core.modifiers/-pewter-tool-modifier/index.html) | Extend this if you want to create a new tool modifier. |
| [com.ejektaflex.pewter.api.core.traits.PewterToolTrait](../com.ejektaflex.pewter.api.core.traits/-pewter-tool-trait/index.html) |  |
| [com.ejektaflex.pewter.api.core.materials.stats.SmeltingStats](../com.ejektaflex.pewter.api.core.materials.stats/-smelting-stats/index.html) |  |
| [com.ejektaflex.pewter.api.core.materials.stats.ToolStats](../com.ejektaflex.pewter.api.core.materials.stats/-tool-stats/index.html) |  |

