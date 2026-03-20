# usercss-font-replace
Simple UserCSS code that allows relatively safe universal variable font replacement and fined tuned customization over exposed variable font features. It is recommended that you use the Stylus extension.

Please note that some websites use custom fonts for symbols, which may break under this extension. Otherwise, this replaces all fonts, including fonts that may be required to maintain the original look that the website author wishes. For sites that you wish to revert the effect, you may click on the Stylus extension, click the three dots next to this userscript, and click "Exclude domain" or "Exclude URL".

Currently, Inter Variable and Cascadia Code are used for body/header font and monospaced font (respectively). It is planned to add more variable fonts over time. 

The options panel allows variable font aware customization of weight, with further non-variable font aware customization of stroke, size, and spacing. 

<img width="363" height="707" alt="options panel" src="https://github.com/user-attachments/assets/0d86ae50-e92e-428b-ade0-a0ace8dc5399" />

It is planned to add in more variable font aware controls over time for the fonts that support it. For example, *[Roboto Flex](https://fonts.google.com/specimen/Roboto+Flex)* supports the following variable font controls:

- Optical Size
- Weight
- Grade
- Slant
- Width
- Thick Stroke
- Thin Stroke
- Counter Width
- Uppercase Height
- Lowercase Height
- Ascender Height
- Descender Depth
- Figure Height

## Installation
Make sure you have the following fonts installed in the system:
- [Inter Variable](https://github.com/rsms/inter)
- [Cascadia Code](https://github.com/microsoft/cascadia-code)

*Note:* Cascadia code comes bundled with Windows Terminal, so there is no need to download if you already have Windows Terminal installed.

Make sure you have the following extension installed:
- [Stylus](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)

*Note:* Other UserCSS extensions may be compatible, but likely require conversion for the GUI to work properly.

Click on "Universal Font Replacement.css" and click "Raw".

## To-Do:
- more body fonts
- variable code fonts
- fine tuned control of more variable (e.g. optical sizing)
- option to toggle font replacement
- separated header font
- use the variable aware version of Cascadia Code
- standardize GUI control units

#### Planned Fonts:
- Roboto Flex
- Atkinson Hyperlegible Next
- Ubuntu Sans

#### Known issues:
- mono weight control doesn't work
- serif fonts are overwritten (unlikely to be fixed due to the limitations of userCSS)
- Cascadia Code is not currently using variable aware controls

## Comparison
*(Click on images to view sharp versions)*
Off:
<img width="822" height="893" alt="Off" src="https://github.com/user-attachments/assets/be6a1002-abc6-4869-bec5-a8613f126150" />

On:
<img width="823" height="909" alt="On" src="https://github.com/user-attachments/assets/21a45302-ccbd-4cd3-b0c7-7fb77bff72c9" />
