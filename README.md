# PlayStation-X ES-DE
A port of the [PlayStation-X](https://github.com/pajarorrojo/es-theme-PlayStation-X) ES theme by [pajarorrojo](https://github.com/pajarorrojo) to ES-DE

## Preview
| PS4 View | PS5 View | 
|----|----|
|<img width="1272" height="712" alt="ps4_cropped" src="https://github.com/user-attachments/assets/4d17f253-7a57-4978-8c65-73b6e0c1746b" />|<img width="1272" height="712" alt="ps5_cropped" src="https://github.com/user-attachments/assets/90bc1cb4-557b-480f-8f63-e0e3b1ec1fc1" />|






| 2D Carousel | 3D Carousel | Grid|
|----|----|----|
|<img width="1272" height="712" alt="2d carousel both_cropped" src="https://github.com/user-attachments/assets/e58e4068-c9d2-4286-851a-14935bd55264" />|<img width="1272" height="712" alt="3d carousel both_cropped" src="https://github.com/user-attachments/assets/4249a428-2521-40d1-a04e-c2368159f270" />|<img width="1272" height="712" alt="grid_cropped" src="https://github.com/user-attachments/assets/d2c04f37-8324-4974-a850-7f936347af4e" />|

## **Configuration Options**

- This theme has a simple set of options that can be changed directly from the UI Settings menu of ES-DE
  
- `Theme Variant` - sets the theme variant adjusting the gamelist view. 
   - `Carousel: Metadata` - Gamelist view with a carousel displaying description metadata
   - `Carousel: Metadata (Video Background)` - Gamelist view with a carousel displaying description metadata, background plays game video
   - `Carousel: Metadata & Miximage` - Gamelist view with a carousel displaying miximage and description metadata
   - `Carousel: Metadata & Miximage with video` - Gamelist view with a carousel displaying miximage with delayed video and description metadata
   - `Grid` - Gamelist view with a grid view with metadata
   - `Textlist` - Gamelist view with a textlist view with metadata

 - `Theme Color Scheme` - sets the system view style based on PS4 or PS5. The custom variants allow for avatar and username customization - see customiztion section.
   - `PS4`
   - `PS5`
   - `PS4 - Custom`
   - `PS5 - Custom`

     
- `Font Size` - enables you to change the size of the fonts displayed in the theme. This also adjusts the size of the system view carousel and gamelist view carousel or grid.
   - `Small`
   - `Medium`
   - `Large`
     
- `Theme Aspect Ratio` - sets the aspect ratio the theme will render at. If needed, this can be changed to match the aspect ratio of your screen (though it should happen automatically).
   - `1:1`
   - `8:7`
   - `5:4`
   - `4:3`
   - `3:2`
   - `16:10`
   - `16:9`
   - `19.5:9`
   - `21:9`
   - `32:9`

## **Customization Options**
A custom color scheme lets you modify some theme options while also allowing you to continue to get updates from the theme downloader.

1) In the resources folder you will find a template file called [customizations.xml](https://github.com/RobZombie9043/playstation-x-es-de/blob/main/resources/customizations.xml)

2) Make a folder named `theme-customizations` and place a copy of the `customizations.xml` file inside that folder.  The folder structure should look like this when you are done:
   ```
   /ES-DE/themes/playstation-x-es-de/theme-customizations/customizations.xml
   ```
   For the Android theme downloader   version this would be:
   
    ```
    Android/data/org.es_de.frontend/files/themes/playstation-x-es-de/theme-customizations/customizations.xml
   ```

4) Edit the properties in `customizations.xml` to make theme customizations

Username and avatar customizations:
   - `<userName>` - the user name to be displayed
   - `<avatarPath>` - path to a custom avatar image to be displayed (Some avatars have been included inside the `ES-DE/themes/playstation-x-es-de/resources/avatars` folder or you can add your own inside the `theme-customization` folder)

System View customizations:
   - `<characterOverlayVisible>` - Set to false to disable the character overlays on system view
   - `<systemVideoVisible>` - Set to false to disable the videos on system view
   - `<secondaryDescriptionPos>` - Set to true to shift description text left, useful to combine with removing videos
   - `<systemVideoAudio>` - Set to false to disable the audio of the system view videos
   - `<systemLogoVisible>` - Set to false to disable the system logo on system view
   - `<systemConsoleVisible>` - Set to false to disable the system console art on system view
   - `<systemBackgroundSolidColor>` - Set to use a solid color background in system view
   - `<systemBackgroundColor>` - sets the color background to be used for above setting

Gamelist View cutsomizations:
   - `<gameBackgroundSolidColor>` - Set to use a solid color background in gamelist view
   - `<gameBackgroundColor>` - sets the color background to be used for above setting
   - `<gameVideoAudio>` - Set to false to disable the audio of the gamelist view videos
   - `<gameVideoDelay>` - Set delay in seconds before video plays
   - `<carouselImageType>` - Type of image to display in gamelist carousel e.g. `cover`, `3dbox`
   - `<metadataImageType>` - Type of image to display in gamelist metadata e.g. `miximage`, `screenshot`, `titlescreen`, `cover`
   - `<gameVideoVisible>` - Set to show game video, if true set `<gameImageVisible>` to `false`
   - `<gameImageVisible>` - Set to show game media image, if true set `<gameVideoVisible>` to `false`   

4) Set the `Theme Color Scheme` in ES-DE's UI Settings menu to `PS4 - Custom` or `PS5 - Custom` and you should see your customizations.  If you see an error check that the paths discussed above are correct and then check that the values you added for each property are correct and well formatted.

## Credits

- Ported from the PlayStation-X ES theme by pajarorrojo - https://github.com/pajarorrojo/es-theme-PlayStation-X
- Many video assets from alpha-es-de by hplant6 - https://github.com/hplant6/alpha-es-de
- Some backgorund image artwork from slick-es-de by Weestuarty - https://github.com/Weestuarty-es-de/slick-es-de
- PS4 Sounds from MrVictorFull57 - https://github.com/MrVictorFull57/iisu-interpreted-es-de/commits?author=MrVictorFull57

## Licence
**Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**
https://creativecommons.org/licenses/by-nc-sa/4.0/

![Creative Commons Licence](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png "Creative Commons Licence")

Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License

You are free to:

- **Share:** copy and redistribute the material in any medium or format
- **Adapt:** remix, transform, and build upon the material

**Under the following terms:**

**Attribution:** You must give appropriate credit, provide a link to the license, and indicate if
changes were made. You may do so in any reasonable manner, but not in any way that suggests the
licensor endorses you or your use.

**NonCommercial:** You may not use the material for commercial purposes.

**ShareAlike:** If you remix, transform, or build upon the material, you must distribute your
contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally
restrict others from doing anything the license permits.
