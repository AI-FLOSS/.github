# X-Tech Laboratories brand

Logos, icons and design rules for X-Tech Laboratories and its projects.

## Logo

| File                                                         | Use                                                 |
| ------------------------------------------------------------ | --------------------------------------------------- |
| [`logo/x-tech-laboratories.svg`](logo/x-tech-laboratories.svg) | The full logo: banners, headers, the website.       |
| [`logo/x-tech.svg`](logo/x-tech.svg)                         | The short logo, where space is tight.               |
| [`icon/icon.svg`](icon/icon.svg)                             | The icon alone: avatars, favicons, app icons.       |
| [`icon/icon-inverted.svg`](icon/icon-inverted.svg)           | The icon in white, for use on a blue background.    |

Each SVG has a PNG next to it. The lettering in the logos is already converted to outlines, so they
look the same without the font installed.

The X is cut out of the hexagon, so the background shows through it. On a dark background, put a
white shape behind the X, or use the inverted icon.

## Colours

| Name       | Hex       | Use                                  |
| ---------- | --------- | ------------------------------------ |
| Baby blue  | `#0088ff` | The brand colour: logo, icon, links. |
| Sky blue   | `#00acff` | The icon pack.                       |
| White      | `#ffffff` | Backgrounds and the X in the icon.   |

## Fonts

- [Rajdhani](https://fonts.google.com/specimen/Rajdhani) Bold, by Indian Type Foundry, for the logo
  and headings.
- [Noto Sans](https://fonts.google.com/noto/specimen/Noto+Sans) for body text.

Both are free under the SIL Open Font License.

## Naming

- Names of X-Tech projects and services begin with `X-` followed by a descriptive word, for example
  X-Notes or X-Security.
- Extra words are joined with more hyphens, for example X-Device-Management-Interface.
- A long name may be shortened to an acronym when that is easier to say, for example XDMI.
- Where a hyphen is not allowed, drop it and use camel case, for example XNotes.

## How the icon and logo are built

The icon is made in Inkscape:

1. Type an "X" in Rajdhani Bold, size 144.
2. Draw a hexagon in `#0088ff` with flat top and bottom sides, the same height as the X.
3. Scale the hexagon to 200% of its width and height.
4. Centre the hexagon and the X on each other, horizontally and vertically.
5. Select both and apply Path → Difference.

The logo adds the name to the icon:

1. Type a hyphen in Rajdhani Bold, size 144, colour `#0088ff`.
2. Place it so its left end touches the hexagon's right corner, centred vertically.
3. Slide it left until the hexagon's sides run smoothly into the top of the hyphen.
4. Continue typing after the hyphen: "Tech" for the short logo, or "Tech Laboratories" for the full one.
5. Convert the text to outlines (Path → Object to Path) before exporting.

## Other artwork

- [`icon-pack/`](icon-pack/) holds hexagon icons for files, folders and media, in sky blue.
- [`x-system.svg`](x-system.svg) is the X-System mark: a hexagon inside a hexagon.
