---
title: com.ejektaflex.pewter.api.core - Pewter
---

[Pewter](../index.html) / [com.ejektaflex.pewter.api.core](./index.html)

## Package com.ejektaflex.pewter.api.core

### Types

| [EffectWrapper](-effect-wrapper/index.html) | `class EffectWrapper<T : `[`IPewterBaseEffect`](-i-pewter-base-effect.html)`>`<br>This is a simple wrapper around an effect that allows you to store a reference to an effect without instantiating it. This is needed because these effects get registered into registries when they're instantiated. Multiple instantiations of a tool effect will then cause an error due to how they're implemented in TiC/ConArm. |
| [IPewterBaseEffect](-i-pewter-base-effect.html) | `interface IPewterBaseEffect : IModifier`<br>A base interface from which all Pewter Tool/Armor Modifier/Traits come from. |
| [PewterModule](-pewter-module/index.html) | `abstract class PewterModule`<br>A [PewterModule](-pewter-module/index.html) is a set of materials, tools and traits. [com.ejektaflex.pewter.api.PewterAPI.registerModule](#) will register this module so that Pewter can load it later on. |

