# Example Theme Archive
At the root of the theme archive, `info.json` file and `icons` folder should exist.

<br>

## `info.json` File
---

key | type | description
----|-----|----
id  | string | must include "glcr-" prefix
name | string | The name of the theme
author | string | The author of the theme
created | string | `new Date().toString()`
updated | string | `new Date().toString()`
icons | Array | *[See example](theme/info.json)*

*See [theme/info.json](theme/info.json) for an example.*

<br>


## `icons/` folder
---
The icons in the icons folder must be a PNG, and named to match the Bundle ID it's targeting.
*See [theme/icons/](theme/icons/) for an example.*

<br>

## Theme Example
---
Download [theme/theme.zip](theme/theme.zip) and import into Glacier to try it out!