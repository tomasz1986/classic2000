# Classic 2000

Classic 2000 is a collection of themes for Windows 8.1 and 10. The themes are based on the classic-style colour schemes from Windows 2000. They are also [high contrast](//msdn.microsoft.com/library/windows/desktop/hh404233%28v=vs.85%29.aspx) with all its [limitations](//docs.microsoft.com/windows/uwp/design/accessibility/high-contrast-themes). Unfortunately, this is the only method to freely customize the colours in Windows 8 and later (without using 3rd party tools or system file modifications).


## Installation

Copy all .theme files from the "Ease of Access Themes" folder to "%WINDIR%\Resources\Ease of Access Themes". You will then be able to use the new themes in [the same way as stock high contrast themes](https://support.microsoft.com/help/13862/windows-use-high-contrast-mode).


## Themes

The following themes are included.

### Original themes

- Windows Classic
- Windows Standard
- Brick
- Desert
- Eggplant
- Lilac
- Maple
- Marine
- Plum
- Pumpkin
- Rainy Day
- Red, White and Blue
- Rose
- Slate
- Spruce
- Storm
- Teal
- Wheat

### Inverted original themes

- Windows Classic (Inverted)
- Windows Standard (Inverted)
- Brick (Inverted)
- Desert (Inverted)
- Eggplant (Inverted)
- Lilac (Inverted)
- Maple (Inverted)
- Marine (Inverted)
- Plum (Inverted)
- Pumpkin (Inverted)
- Rainy Day (Inverted)
- Red, White, and Blue (Inverted)
- Rose (Inverted)
- Slate (Inverted)
- Spruce (Inverted)
- Storm (Inverted)
- Teal (Inverted)
- Wheat (Inverted)

### Modified themes

- Windows Standard (Warm)
- Windows Standard (Warm Inverted)


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