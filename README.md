# garlicoin graphic assets
Non-development Graphic Assets for Garlicoin: Logos, Breadwallets, Breadnotes, etc…

**PRs Welcome**

## At a Glance Branding Details
### Colors:
#### Brand Yellow
`#FCD46B`

* color of garlicoin logo

##### Brand Grey
`#505566`

* color of garlicoin logo text

### Typography:
### Main Typeface
[**Arimo**](https://fonts.google.com/specimen/Arimo) - Google Fonts

* Sans serif garlicoin logo text

### Secondary Typeface
[**Source Code Pro**](https://fonts.google.com/specimen/Source+Code+Pro) - Google Fonts

* Monospace font for wallet addresses and private keys


## Repo and Asset Details
### Folder Structure
Each broad item (logo, breadwallet, breadnotes, etc…) is given a root level folder. Within those Sourcefile, SVG export, and PNG export are given folders to contain their assets.

All `sourcefile` folders should contain a single file which has all versions (colors, demos, templates, etc…)

For `logomark` and `logo+text` the assets are exported in color, black with transparent background, and white with transparent background.

### Sizing & Cropping
`logomark` is cropped to the logo's edges, and is sized proportionally down to `100px` wide.

`logo+text` is cropped to corresponding spacing guidelines. The logomark within this is sized the same as `logomark`.

`breadnote` and `breadwallet` are both `1500px` by `800px` which will scale down to `5in` by `2.66in` when printed at 300px.
Bleed and Cropmarks are not included, the rationale being that garlicoins general audience will be unfamiliar with such printing conventions.
