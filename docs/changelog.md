# Changelog of the Burn-My-Windows Extension

## [Burn My Window 7](https://github.com/schneegans/Burn-My-Windows/releases/tag/v7)

**Release Date:** 2022-01-03

#### New Features

* Add the option to use a 3D noise for the fire shader. This will add some more temporal variation to the flames at the cost of slightly decreased rendering performance.
* Added a changelog entry to the menu of the preferences dialog.

#### Fixes

* Resolve copyright issues by using a MIT-licensed noise implementation.


## [Burn My Window 6](https://github.com/schneegans/Burn-My-Windows/releases/tag/v6)

**Release Date:** 2022-01-02

#### Fixes

* Removed a debug log message.

## [Burn My Window 5](https://github.com/schneegans/Burn-My-Windows/releases/tag/v5)

**Release Date:** 2022-01-02

#### New Features

* Added a new ridiculous close-animation: the T-Rex-Attack!
* Added a new simple close-animation: the TV-Effect!
* Added a menu to the preferences dialog with links for bug reporting and donations.

#### Other Enhancements

* The fire shader now uses a `smoothstep` to make it less blocky.

#### Bug Fixes

* Fixed a bug which messed up the overview of GNOME Shell 3.36.

## [Burn My Window 4](https://github.com/schneegans/Burn-My-Windows/releases/tag/v4)

**Release Date:** 2021-12-25

#### New Features

* Added a new Matrix shader which dissolves your windows in a shower of green letters. You can switch between the fire and the matrix shader in the settings. Sadly, this effect cannot be available under GNOME 3.3x as it was apparently impossible to set textures for a `Clutter.ShaderEffect` in GJS back then.
* Added a setting to apply the animation also for closing dialog windows.

#### Other Enhancements

* Refactored the code a lot to make it easier to add new shader effects in the future.
* Tweaked timing of the fire shader. Previously, the fire became invisible quite quickly. Due to this new animation timing, the default animation time has been reduced to 1500 ms.

## [Burn My Window 3](https://github.com/schneegans/Burn-My-Windows/releases/tag/v3)

**Release Date:** 2021-12-20

#### New Features

* Add support for GNOME 3.36 and GNOME 3.38.

## [Burn My Window 2](https://github.com/schneegans/Burn-My-Windows/releases/tag/v2)

**Release Date:** 2021-12-16

#### New Features

* Added the possibility to adjust fire colors.
* Added the possibility to adjust flame speed and scale.
* Added some fire presets.

## [Burn My Window 1](https://github.com/schneegans/Burn-My-Windows/releases/tag/v1)

**Release Date:** 2021-12-14

* Initial publication on GitHub supporting GNOME 40 and GNOME 41.
