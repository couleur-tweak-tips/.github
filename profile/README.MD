<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/cgYALQO.png">
  <source media="(prefers-color-scheme: light)" srcset="https://i.imgur.com/rSlRjax.png">
  <img>
</picture>

## Links

* Discord (join us!): [discord.gg/CTT](https://discord.com/invite/aPVMJy78Pa)
* Website: [ctt.cx](https://ctt.cx)
* Twitter: [@couleurtweaks](https://twitter.com/@CouleurTweaks)

# Ongoing Projects



## <img src="https://raw.githubusercontent.com/PowerShell/PowerShell/master/assets/ps_black_64.svg?sanitize=true" alt="PS7 logo" width="24" /> [TweakList](https://github.com/couleur-tweak-tips/TweakList)

###### `"Stable" 🟢`

Lightweight and easy to use collection of PowerShell functions which can be ran with a single command. The `Optimize-` functions (such as `Optimize-LunarClient` or `Optimize-OBS`) will tweak the specified program's settings files.  Most of them prompt the user with a list of tweaks to apply. Settings are applied using serialization, meaning unrelated settings (like keybinds) aren't overwritten.

## <img alt="Smoothie" src="https://i.imgur.com/K20ymPM.png" width="20" /> [Smoothie](https://github.com/couleur-tweak-tips/smoothie) (currently being rewritten @ [smoothie-rs](https://github.com/couleur-tweak-tips/smoothie-rs))

###### `Currently migrating languages 🟠`

Highly customizable program, based on VapourSynth, which can add motion blur to video game footage. See the [demo playlist](https://www.youtube.com/playlist?list=PLrsLsEZL_o4M_yTqZGwN5cM5ZxJTqkWkZ) for examples.

## suckless-cut

###### `Not yet functional, not motivated to maintain 🔴`

Lua-based mpv script to cut your videos in a similar fashion to the electron based (and thus slow 😢) [LosslessCut](https://github.com/mifi/Lossless-Cut).

# Deprecated Repositories

Development of these is paused and/or not a priority 👍

## [🧧 utils](https://github.com/couleur-tweak-tips/utils)
###### Now only used as a [Scoop bucket](https://github.com/couleur-tweak-tips/utils/tree/main/bucket), see [/bucket/](https://github.com/couleur-tweak-tips/utils/tree/main/bucket)

Legacy repository that held PowerShell functions.

## [🌙 Moony](https://github.com/couleur-tweak-tips/Moony)

###### `Keeps breaking, PRs are open 🟣`

Minimalistic and unrestricted third-party [Lunar Client](https://lunarclient.com) launcher

## [🌳 Show-ModuleTree](https://github.com/couleur-tweak-tips/Show-ModuleTree)

###### `Lack of interest (most of the code is already present) 💀`

Generates a bird's-eye view of a PowerShell module and the contents of its .ps1 files.

* [/src/](https://github.com/couleur-tweak-tips/Show-ModuleTree/tree/master/src)
  * [/Public/](https://github.com/couleur-tweak-tips/Show-ModuleTree/tree/master/src/Public)
    * [Test.ps1](https://github.com/couleur-tweak-tips/Show-ModuleTree/tree/master/src/Public/Test.ps1)
      * Function ``Invoke-Foo`` - Generates a display of the Baz
      * Filter ``Select-Bar``
    * [/NestedPublicFolder/](https://github.com/couleur-tweak-tips/Show-ModuleTree/tree/master/src/Public/NestedPublicFolder)
      * [NestedPublicFile.ps1]()
         * Function ``Booz`` - Does Bawz
   * [/Private/](https://github.com/couleur-tweak-tips/Show-ModuleTree/tree/master/src/Private)
     * PrivateFile.ps1
       * function ``Show-PrivateFunction`` - I think you get the point...
