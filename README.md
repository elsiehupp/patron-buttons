# SVG Patron Buttons

This repository contains SVG buttons for linking to a Patreon.

## Impetus

I made these SVG files because I ran into instances of people using:

1. "Become a Patron" banners that were low-resoluton (i.e. not Retina)
2. "Become a Patron" banners didn't use Patreon's 2020 brand colors

## Contents

This repository contains various colorways of the following:

* 4x1 banners closely matching Patreon's existing "Become a Patron" banners
* 8x5 banners with text but no Patreon logo (i.e. roughly a golden ratio, which WordPress seems to prefer)

## Editing

I tried to make these SVG files as simple as possible. There are SVG entities with the ids `background`, `logo`, and `text`. You can edit this files in any software that supports editing SVG, though your resulting export might have a lot more cruft.

You can export these images as PNGs if you want, but the SVGs should work in any modern web browser, though you will probably need to explicitly specify your desired display dimensions.

## Contributing

If you want to add versions of these banners in slightly different aspect ratios, feel free to do a pull request. I will help you clean up the SVG markup to make it as a minimal as possible.

## Example Usage

If you use WordPress and add one of these to your `wp-content/uploads` folder, you should be able to use code something like the following:

```html
<a href="https://www.patreon.com/example_name">
    <img width="200px" height="50px" alt="Become a Patron" src="https://www.example.com/wp-content/uploads/become_a_patron_4x1_black_logo_coral_text_on_white.svg">
</a>
```

Honestly this is just supposed to be a drop-in replacement for whatever asset you already have. Please do not ask me for support.

## License

These images use Patreon brand identity (which is trademarked), and if you use them, you must follow [Patreon's brand guidelines](https://www.patreon.com/brand/guidelines).

These images use the font [GT-America](https://gt-america.com/) (which is used by Patreon's existing "Become a Patron" buttons and is protected by copyright) but do not include a reusable copy of the font.

Notwithstanding the above, the contents of this repository are subject to the [CC0 1.0 Universal (CC0 1.0)
Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).