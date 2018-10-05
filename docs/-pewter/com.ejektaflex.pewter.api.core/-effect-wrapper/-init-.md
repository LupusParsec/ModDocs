---
title: EffectWrapper.<init> - Pewter
---

[Pewter](../../index.html) / [com.ejektaflex.pewter.api.core](../index.html) / [EffectWrapper](index.html) / [&lt;init&gt;](./-init-.html)

# &lt;init&gt;

`EffectWrapper(identifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, func: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`.() -> `[`T`](index.html#T)`)`

This is a simple wrapper around an effect that allows you to store a
reference to an effect without instantiating it. This is needed because
these effects get registered into registries when they're instantiated.
Multiple instantiations of a tool effect will then cause an error due
to how they're implemented in TiC/ConArm.

