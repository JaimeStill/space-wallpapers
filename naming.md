# Naming Convention

## Files

> `{id}` represents the unique identifier provided to the file from the source. For instance, hubble images example

File | Description | Name
-----|-------------|-----
`.tif` | Original Raw Image | `{id}.tif`
`.xcf` | GIMP Project | `{id}.xcf`
`.png` | Wallpaper | `{id}.{width}-{height}.png`

> Each directory has a `thumb.png` that's a `1024x{scaled-height}` preview of the image.

## Directories

`{source}-{identifier}`

Source | Agency | URL
-------|--------|----
`eso` | European Southern Observatory | https://www.eso.org/public/images
`hst` | Hubble Space Telescope | https://www.spacetelescope.org/images