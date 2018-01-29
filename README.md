# Classic 2000

Classic 2000 is a collection of themes for Windows 8.1 and 10. The themes are based on the classic-style colour schemes from Windows 2000. They are also [high contrast](//msdn.microsoft.com/library/windows/desktop/hh404233%28v=vs.85%29.aspx) with all its [limitations](//docs.microsoft.com/windows/uwp/design/accessibility/high-contrast-themes). Unfortunately, this is the only method to freely customize the colours in Windows 8 and later (without using 3rd party tools or system file modifications).


## Installation

Copy all .theme files from the "Ease of Access Themes" folder to "%WINDIR%\Resources\Ease of Access Themes". You will then be able to use the new themes in [the same way as stock high contrast themes](https://support.microsoft.com/help/13862/windows-use-high-contrast-mode).


## Themes

The following themes are included.

### Original themes

- Windows Classic
  <br><img src="preview/Classic%202000%20Windows%20Classic.png" width="512">

- Windows Standard
  <br><img src="preview/Classic%202000%20Windows%20Standard.png" width="512">

- Brick
  <br><img src="preview/Classic%202000%20Brick.png" width="512">

- Desert
  <br><img src="preview/Classic%202000%20Desert.png" width="512">

- Eggplant
  <br><img src="preview/Classic%202000%20Eggplant.png" width="512">

- Lilac
  <br><img src="preview/Classic%202000%20Lilac.png" width="512">

- Maple
  <br><img src="preview/Classic%202000%20Maple.png" width="512">

- Marine
  <br><img src="preview/Classic%202000%20Marine.png" width="512">

- Plum
  <br><img src="preview/Classic%202000%20Plum.png" width="512">

- Pumpkin
  <br><img src="preview/Classic%202000%20Pumpkin.png" width="512">

- Rainy Day
  <br><img src="preview/Classic%202000%20Rainy Day.png" width="512">

- Red, White and Blue
  <br><img src="preview/Classic%202000%20Red,%20White%20and%20Blue.png" width="512">

- Rose
  <br><img src="preview/Classic%202000%20Rose.png" width="512">

- Slate
  <br><img src="preview/Classic%202000%20Slate.png" width="512">

- Spruce
  <br><img src="preview/Classic%202000%20Spruce.png" width="512">

- Storm
  <br><img src="preview/Classic%202000%20Storm.png" width="512">

- Teal
  <br><img src="preview/Classic%202000%20Teal.png" width="512">

- Wheat
  <br><img src="preview/Classic%202000%20Wheat.png" width="512">

### Inverted original themes

- Windows Classic (Inverted)
  <br><img src="preview/Classic%202000%20Windows%20Classic%20(Inverted).png" width="512">

- Windows Standard (Inverted)
  <br><img src="preview/Classic%202000%20Windows%20Standard%20(Inverted).png" width="512">

- Brick (Inverted)
  <br><img src="preview/Classic%202000%20Brick%20(Inverted).png" width="512">

- Desert (Inverted)
  <br><img src="preview/Classic%202000%20Desert%20(Inverted).png" width="512">

- Eggplant (Inverted)
  <br><img src="preview/Classic%202000%20Eggplant%20(Inverted).png" width="512">

- Lilac (Inverted)
  <br><img src="preview/Classic%202000%20Lilac%20(Inverted).png" width="512">

- Maple (Inverted)
  <br><img src="preview/Classic%202000%20Maple%20(Inverted).png" width="512">

- Marine (Inverted)
  <br><img src="preview/Classic%202000%20Marine%20(Inverted).png" width="512">

- Plum (Inverted)
  <br><img src="preview/Classic%202000%20Plum%20(Inverted).png" width="512">

- Pumpkin (Inverted)
  <br><img src="preview/Classic%202000%20Pumpkin%20(Inverted).png" width="512">

- Rainy Day (Inverted)
  <br><img src="preview/Classic%202000%20Rainy%20Day%20(Inverted).png" width="512">

- Red, White, and Blue (Inverted)
  <br><img src="preview/Classic%202000%20Red,%20White,%20and%20Blue%20(Inverted).png" width="512">

- Rose (Inverted)
  <br><img src="preview/Classic%202000%20Rose%20(Inverted).png" width="512">

- Slate (Inverted)
  <br><img src="preview/Classic%202000%20Slate%20(Inverted).png" width="512">

- Spruce (Inverted)
  <br><img src="preview/Classic%202000%20Spruce%20(Inverted).png" width="512">

- Storm (Inverted)
  <br><img src="preview/Classic%202000%20Storm%20(Inverted).png" width="512">

- Teal (Inverted)
  <br><img src="preview/Classic%202000%20Teal%20(Inverted).png" width="512">

- Wheat (Inverted)
  <br><img src="preview/Classic%202000%20Wheat%20(Inverted).png" width="512">

### Modified themes

- Windows Standard (Warm)
  <br><img src="preview/Classic%202000%20Windows%20Standard%20(Warm).png" width="512">

- Windows Standard (Warm Inverted)
  <br><img src="preview/Classic%202000%20Windows%20Standard%20(Warm%20Inverted).png" width="512">


## Customization

Use the following resources to further modify the themes to your liking.

- http://msdn.microsoft.com/library/windows/desktop/bb773190%28v=vs.85%29.aspx
- http://neowin.net/forum/topic/624901-windows-colors-explained


## Bugs & Issues

### Theme Issues

#### 1. Incorrect desktop colour and font
Your desktop background may be displayed in an extensively bright colour after applying some of the themes. The font may also look unnaturally bold and bulky. This is a bug with high contrast themes that goes away after either rebooting or logging out and in.

#### 2. InactiveTitleText illegible contrast
The actual colour of InactiveTitleText may not match the value declared in its .theme file. The text is usually darker and much less contrasty, and as a result more difficult to read. To overcome this issue you must set its value to a brighter colour than in the original theme, e.g. "InactiveTitleText=255 255 255" instead of "InactiveTitleText=212 208 200" in case of Windows Standard.

#### 3. Window colour limitation
In the original Windows classic themes it was possible to define Window and 3D Objects (buttons, menu, etc.) colours separately. High contrast themes do not have this option. Therefore, in order to keep a consistent look, both Window and 3D Object must use the exact same colour, e.g. "Window=212 208 200" instead of "Window=255 255 255" in case of Windows Standard.

### High Contrast Issues

Enabling High Contrast mode in Windows 8 and later changes much more than just the system interface. It also affects the look of most programs, and even how websites are displayed. The former may render some of the programs illegible, or even unusable. The latter can usually be disabled in web browsers, although not in Internet Explorer and Edge. Thus, you should be aware of such limitations when applying the themes listed here. If you find them too cumbersome or difficult to use, feel free to simply revert to your original Windows theme.


## Uninstallation

Delete all .theme files starting with "Classic 2000" from the "%WINDIR%\Resources\Ease of Access Themes" folder.