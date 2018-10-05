---
title: EffectWrapper - Pewter
---

[Pewter](../../index.html) / [com.ejektaflex.pewter.api.core](../index.html) / [EffectWrapper](./index.html)

# EffectWrapper

`class EffectWrapper<T : `[`IPewterBaseEffect`](../-i-pewter-base-effect.html)`>`

This is a simple wrapper around an effect that allows you to store a
reference to an effect without instantiating it. This is needed because
these effects get registered into registries when they're instantiated.
Multiple instantiations of a tool effect will then cause an error due
to how they're implemented in TiC/ConArm.

### Constructors

| [&lt;init&gt;](-init-.html) | `EffectWrapper(identifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, func: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.() -> `[`T`](index.html#T)`)`<br>This is a simple wrapper around an effect that allows you to store a reference to an effect without instantiating it. This is needed because these effects get registered into registries when they're instantiated. Multiple instantiations of a tool effect will then cause an error due to how they're implemented in TiC/ConArm. |

### Properties

| [func](func.html) | `val func: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.() -> `[`T`](index.html#T) |
| [identifier](identifier.html) | `var identifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| [create](create.html) | `fun create(): `[`T`](index.html#T) |

