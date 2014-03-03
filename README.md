# Crossass Live Templates

The [Crossass](https://github.com/whizark/crossass) Live Templates for JetBrains IntelliJ IDEA family (PhpStorm, WebStorm etc.),
which also includes Live Templates for other Crossass components as below.

 * [Crosass Configuration](https://github.com/whizark/crossass-config)
 * [Crossass Inspector](https://github.com/whizark/crossass-inspector)
 * [Crosass Mem](https://github.com/whizark/crossass-mem)

## Installation

 1. Copy `Crossass.xml` into the following location.
 2. Restart your IDE.

### Linux

`~\.<product name><version number>\config\templates`

e.g. `~\.WebIde70\config\templates`

### Mac OS X

`~/Library/Preferences/<product name><version number>/templates`

e.g. `~/Library/Preferences/WebIde70/templates`

### Windows

`<your home directory>\.<product name><version number>\config\templates`

e.g. `username\.WebIde70\config\templates`

## Tips

Some Crossass Live Templates also produce Custom Region with folding markers so that you can easily navigate between Modules / Modifiers.

To invoke the navigation, press `Ctrl + Alt + Period` (Linux / Windows) / `Command + Option + Period` (Mac OS X), or choose `Navigate` > `Custom Region` on the main menu.

## Live Templates

 * x:module (Module)
 * x:module-extend (Extend Module)
 * x:modifier (Modifier)
 * x:bem:element (BEM Element)
 * x:bem:modifier (BEM Modifier)
 * x:parent (Extend parent Modifier)
 * x:export (Export Module)
 * x:import (Import Module)
 * x:extend (Extend Placeholder(s))
 * x:extend-module (Extend Module with Modifier(s))
 * x:extend-modifier (Extend Module's Modifier(s))
 * x:function:root (Module root's Placeholder)
 * x:function:module-name (Module name)
 * x:function:module-parent (Module parent's name)
 * x:inspect (Inspect variable)
 * x:config: (Define configuration value)
 * x:config:default (Define default configuration value)
 * x:config:function (Configuration value)
 * x:config:function:default (Default configuration value)
 * x:mem:base (Define base mem value)
 * x:mem:function (Mem to rem)
 * x:mem:function:fallback (Mem to px for fallback)
 * x:mem:function:base (Base mem value)
 * x:mem:function:base-fallback (Base mem value for fallback)
 * x:rem:function:base (Base rem value)
 * x:rem:function:calc (Px to rem)
