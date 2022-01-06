# Glacier
A non-jailbreak theming platform.

**Note:** This repository is only for documentation, and not the source code itself.


## Themes
---
The goal of Glacier is to allow users to create themes, exporting a theme to share, and importing a theme from other creators.

## Archive Format
---
Visit [examples](examples/) for details.

## Repositories
---
Repos in Glacier are designed specifically for Glacier. Unfortunately, jailbreak repositories don't work in Glacier.

Below is the format a Glacier repository should follow.

### `glcr.json` File
```json
{
    "info": {
        "name": "Repository Name",
        "maintainer": "Repo Owner"
    },
    "themes": [
        {
            "name": "Theme Name",
            "author": "Theme Author",
            "url": "http://example.com/themes/theme_name.zip"
        }
    ]
}
```

### `glcr.png` File
A PNG image file relative to where `glcr.json` is hosted. This will be used as the repository's Icon.

See a live example at https://repo.s0n1c.ca/glcr.json. Icon at https://repo.s0n1c.ca/glcr.png