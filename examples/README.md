# Example Theme Archive
At the root of the theme archive, `info.json` file and `icons` folder should exist.

<br>

## `info.json` File
---

```json
{
    "id": "glcr-a_unique_id", // "glcr-" prefix is required
    "name": "Example Theme",
    "author": "John Doe",
    "created": "Tue Jan 05 2022 16:34:00 GMT-0500 (Eastern Standard Time)",
    "updated": "Tue Jan 05 2022 16:34:00 GMT-0500 (Eastern Standard Time)",
    /* The two dates above are the result of (new Date()).toString() */
    "icons": [
        // For every icon added to icons folder, document its Name and corresponding Bundle ID in here.
        {
            "name": "Twitter",
            "bundle_id": "com.atebits.Tweetie2"
        }
    ]
}
```
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