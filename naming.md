# File Naming Convention

> `{id}` represents the unique identifier provided to the file from the source. For instance, hubble images example

File | Description | Name
-----|-------------|-----
`.tif` | Original Raw Image | `{id}.tif`
`.xcf` | GIMP Project | `{id}.xcf`
`.png` | Wallpaper | `{id}.{width}-{height}.png`

> Each directory has a `thumb.png` that's a `1024x{scaled-height}` preview of the image.