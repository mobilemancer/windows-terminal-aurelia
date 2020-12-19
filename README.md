# Aurelia Retro - a Windows Terminal theme

![alt text][logo]

[logo]: https://raw.githubusercontent.com/mobilemancer/windows-terminal-aurelia/master/demo.jpg "Aurelia theme for Windows Terminal"

## Installation

1. Open your Windows Terminal "LocalState" folder

   ```
   %LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
   ```

2. Copy profiles.json (or rename it) to save it, in case you want to revert the changes.

3. Copy everything in from the profile folder in this repository into to your LocalState folder

## Fonts

The theme is using Cascadia Code.

Information on how to download Cascadia Code can be found here: <https://github.com/microsoft/cascadia-code>

 If you like to use another font, just change the fontFace property in profiles.json.
 
 ## Image to large!
 
 There's a smaller image to use if the default one feels too large. Just edit the background image property and substitute "au-os-L.png" for "au-os-M.png".

 ## Matching Oh my Posh theme

 I made a matching theme for Oh my Posh 3. It looks like the following:

![alt text][img1]

[img1]: https://raw.githubusercontent.com/mobilemancer/windows-terminal-aurelia/master/purple-man-retro.jpg "With Retro Terminal Effect"

Without the Retro Terminal effect:

![alt text][img2]

[img2]: https://raw.githubusercontent.com/mobilemancer/windows-terminal-aurelia/master/purple-man.jpg "Without Retro Terminal Effect"

To use the Posh Theme
   1. install Oh my Posh 3;
   2. copy the theme file, purple-man.json, from the posh-theme folder;
   3. edit your PowerShell profile and set the theme there.
   
To make all the glyphs work as intended, you need to switch to a font that supports Power Line glyphs. 
I recommend Caskaydia Cove, a Cascadia Code version patched with the required glyphs. You can find it on NerdFonts.com or via direct link here: <https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/CascadiaCode.zip>
