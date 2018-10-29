The Hero will be located in an isolated area called Hero Zone, which must be mapped to be in its own tab where only the Hero will be added.

## Structure

| Field Name    | Type            | Required | Details           |
|:------------- |:---------------:|:---------:|:------------------|
| Title         | Plain Text      |     No    | Rendered as H3    |
| Description   | Long Text       |     No    | With WYSIWYG and characters counting, limit to 200 |
| Overlay       | Color           |     Yes   | RGBA value (color + opacity), defaulted to `rgba(0, 0, 0, 0)` |
| Video         | Video Embed     |     No    | Vimeo and Youtube |
| Image         | Image           |     No    | jpg, jpeg, png, gif, aspect ratio 8:3 1600x600 |
| Image Size    | list(Text)      |     No    | Image styles options (1600x600 and 1600x300) |

## Editor Validations (js on the node form)

* There must exist either an Image or a Video so the paragraph can't be saved without one of them, this doesn't mean that both are required, only one of them is no matter which one.
* If the Image field is selected the Image size field appears to allow the Editor pick between two options.

## Design
![Hero](./assets/hero.png)


