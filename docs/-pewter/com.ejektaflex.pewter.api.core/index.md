[Pewter](../index.md) / [com.ejektaflex.pewter.api.core](./index.md)

## Package com.ejektaflex.pewter.api.core

### Types

| Name | Summary |
|---|---|
| [EffectWrapper](-effect-wrapper/index.md) | `class EffectWrapper<T : `[`IPewterBaseEffect`](-i-pewter-base-effect.md)`>`<br>This is a simple wrapper around an effect that allows you to store a reference to an effect without instantiating it. This is needed because these effects get registered into registries when they're instantiated. Multiple instantiations of a tool effect will then cause an error due to how they're implemented in TiC/ConArm. |
| [IPewterBaseEffect](-i-pewter-base-effect.md) | `interface IPewterBaseEffect : IModifier`<br>A base interface from which all Pewter Tool/Armor Modifier/Traits come from. |
| [PewterModule](-pewter-module/index.md) | `abstract class PewterModule`<br>A [PewterModule](-pewter-module/index.md) is a set of materials, tools and traits. [com.ejektaflex.pewter.api.PewterAPI.registerModule](#) will register this module so that Pewter can load it later on. |
