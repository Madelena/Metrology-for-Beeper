# Metrology for Beeper

Metrology is a series of app customizations and redesigns aimed at bringing a bold, clear, and consistent user experience to various apps, such as [Home Assistant](https://github.com/Madelena/Metrology-for-Hass), [MusicBee](https://github.com/Madelena/Metrology-for-Musicbee), and [more](https://github.com/Madelena?tab=repositories&q=Metrology). Its design language is based on [Metro](https://en.wikipedia.org/wiki/Metro_(design_language)) and [Fluent](https://www.microsoft.com/design/fluent/) design systems pioneered by Microsoft Design since the 2010s.

This is a theme for [Beeper](https://www.beeper.com/), a brand-new universal chat client!

![image](https://user-images.githubusercontent.com/4341881/208801279-b820af88-176b-4553-93fd-682eddf0d386.png)
*Dark Theme*

![image](https://user-images.githubusercontent.com/4341881/208801551-3e1e637b-bd79-40f8-850b-26322019f49e.png)
*Light Theme*

## How to Install

To install, simply copy and paste [the CSS code](https://raw.githubusercontent.com/Madelena/Metrology-for-Beeper/main/Metrology-for-Beeper.css) to the Custom CSS box under Settings > Appearances, and you're all set.

As theming for Beeper is still at an early stage of development, so any new updates may break the theme. As a precaution, the app will reset to the base theme every time the app is restarted. You will need to go back into Settings > Appearance and press the Apply button to reapply the theme each time.

## How to Change Colors

![image](https://user-images.githubusercontent.com/4341881/184789498-0aa9a568-6c49-40e4-bd50-e76de17eb9df.png)

The default color is set to magenta (my favorite), and you are not limited to that! Simply change the first line:
```css
--metrology-hue: 212;
```
Enter a number between 0 to 355, and you are all set!
(0 = red, 30 = orange, 60 = yellow, 120 = green, 180 = teal, 210 = blue, 300 = purple)
