<img alt="Modern Inverted Mouse Cursors for Windows" src="./screenshots/title.png" />

[![GitHub Release](https://img.shields.io/github/v/release/emvaized/modern_inverted_mouse_cursors?&label=latest+release)](https://github.com/emvaized/modern_inverted_mouse_cursors/releases)
[![GitHub Downloads (specific asset, all releases)](https://img.shields.io/github/downloads/emvaized/modern_inverted_mouse_cursors/total?label=downloads&logo=github)](https://github.com/emvaized/modern_inverted_mouse_cursors/releases)
[![DeviantArt Views](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fbackend.deviantart.com%2Foembed%3Furl%3Dhttps%3A%2F%2Fwww.deviantart.com%2Femvaized%2Fart%2FModern-Inverted-Mouse-Cursors-for-Windows-10-11-1016675934&query=%24.community.statistics._attributes.views&logo=DeviantArt&logoColor=00e59b&label=views&labelColor=black&color=grey)](https://www.deviantart.com/emvaized/art/Modern-Inverted-Mouse-Cursors-for-Windows-10-11-1016675934)
[![DeviantArt Downloads](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fbackend.deviantart.com%2Foembed%3Furl%3Dhttps%3A%2F%2Fwww.deviantart.com%2Femvaized%2Fart%2FModern-Inverted-Mouse-Cursors-for-Windows-10-11-1016675934&query=%24.community.statistics._attributes.downloads&label=downloads&logo=DeviantArt&logoColor=00e59b&labelColor=black&color=grey)](https://www.deviantart.com/emvaized/art/Modern-Inverted-Mouse-Cursors-for-Windows-10-11-1016675934)

<!-- [![DeviantArt](https://img.shields.io/badge/DeviantArt-grey?logo=deviantart&logoColor=green&labelColor=black)](https://www.deviantart.com/emvaized/art/Modern-Inverted-Mouse-Cursors-for-Windows-10-11-1016675934) -->


This project aims to recreate standard inverted mouse cursors with a more modern design. This cursor inverts the colors behind it, and this way it always stands out no matter the background. Although this feature was initially designed for people with vision problems, regular people could greatly benefit from it as well. Original inverted mouse cursors, available in Windows out the box, hasn't been updated for decades and look quite outdated as for now. This project intends to fix it by providing overhauled inverted mouse cursors. 

Design is mostly inspired by standard Aero mouse cursor in Windows 10/11, but few design changes were made to improve visibility specifically for inverted cursors.

All cursors invert colors behind them, e.g. they become white on dark background, and black on light background: &nbsp;

<img src="./screenshots/illustration_of_inversion.gif" align="top"/>

## Showcase
<img src="./screenshots/all_cursors_no_title.png" />

## How to install: 
1. Click green button "Code" > "Download ZIP"
2. Extract downloaded .zip archive to any folder
3. Locate `cursors/Install.inf` file for "regular" or "no tail" style, right click on that `.inf` file and select "Install"
3. Open Control Panel and navigate to "Mouse Properties" > "Pointers"
4. Select the style you installed and click "Apply"
5. (optional) Double click any cursor type and select any other desired cursor from the extracted folder, if you want alternative version

## How to modify cursors? 
All cursors were created using [Realworld Cursor Editor](http://www.rw-designer.com/cursor-maker) — feel free to use this free tool to modify them for your needs! 
You can also suggest your changes by opening a new [pull request](https://github.com/emvaized/modern_inverted_mouse_cursors/compare) here on Github, or request them by opening a new [issue ticket](https://github.com/emvaized/modern_inverted_mouse_cursors/issues/new).

## Why all cursors are 1-bit?
Color inversion feature is not supported on regular 32-bit cursors. This also leads to semitransparency not available — all pixels in inverted cursors can only be either fully opaque, transparent or inverted. That's why you may notice some chopiness on curves in this cursor pack (so called pixel ladders).

At first I made these cursors 24-bit, but I noticed that in some apps (Microsoft Edge, Krita, CS2) in some occasions cursor suddenly stops inverting colors behind it and becomes all-white, with even black borders dissapearing. Maybe it's some videodrivers issue specific to my computer. But I found out that it doesn't happen if cursor is set to 1-bit mode (black and white) — cursor will still flicker in such situations, but it keeps showing black borders and remains clearly visible. 

Therefore I converted most of cursors in this pack to 1-bit color depth. As an upside, their size is greatly smaller than regular version (2.19kbs per cursor compared to 22.9kbs), while they look and feel pretty much the same. Also, default inverted cursors in Windows are also 1-bit, so it's probably the right way to do it. 


## Support
If you really enjoy this project, please consider supporting its further development by making a small donation! 

<a href="https://ko-fi.com/emvaized"><img src="https://cdn.prod.website-files.com/5c14e387dab576fe667689cf/64f1a9ddd0246590df69ea0b_kofi_long_button_red%25402x-p-800.png" alt="Support on Ko-fi" height="40"></a> &nbsp; <a href="https://liberapay.com/emvaized/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg" height="40"></a> &nbsp; <a href="https://emvaized.github.io/donate/bitcoin/"><img src="https://github.com/emvaized/emvaized.github.io/blob/main/donate/bitcoin/assets/bitcoin-donate-button.png?raw=true" alt="Donate Bitcoin" height="40" /></a>
