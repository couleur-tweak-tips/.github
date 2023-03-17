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

###### `""""Stable""" 🟢`

Lightweight and easy to use collection of PowerShell functions which can be ran with a single command  The `Optimize-` functions will tweak a specified program's settings file (e.g `Optimize-LunarClient` / `Optimize-OBS`).  Most of them let you you get prompted with a list of tweaks to tick, note it will cleverly modify settings. (it uses serialization instead of outright overwriting your files, your other personal settings won't be lost)

## <img alt="Smoothie" src="https://i.imgur.com/K20ymPM.png" width="20" /> [Smoothie](https://github.com/couleur-tweak-tips/smoothie) (currently being rewritten @ [smoothie-rs](https://github.com/couleur-tweak-tips/smoothie-rs))

###### `Currently migrating language 🟠`

Highly customizable motion-blur effect suite for video-game footage (based on VapourSynth), see the [demo playlist](https://www.youtube.com/playlist?list=PLrsLsEZL_o4M_yTqZGwN5cM5ZxJTqkWkZ) for examples

## suckless-cut

###### `Not functional yet 🔴`

lua-based mpv script to cut your videos in a very similar fashion to the electron based (AKA slow 😢) [LosslessCut](https://github.com/mifi/Lossless-Cut)

# Miscellaneous Projects

Theses are either not on priority or paused 👍

## [🌙 Moony](https://github.com/couleur-tweak-tips/Moony)

###### `Keeps breaking, PRs open 🟣`

Minimalistic and unlocked third-party [Lunar Client](https://lunarclient.com) launcher

## [🌳 Show-ModuleTree](https://github.com/couleur-tweak-tips/Show-ModuleTree)


###### `Lack of interest (a good part of the code is present) 💀`

Generates a bird's view of your PowerShell module and it's .ps1 files' content

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
       * function ``Show-PrivateFunction`` - I think I got to the point..