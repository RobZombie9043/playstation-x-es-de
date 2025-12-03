# PlayStation-X-es-de
A port of the [PlayStation-X](https://github.com/pajarorrojo/es-theme-PlayStation-X) ES theme by [pajarorrojo](https://github.com/pajarorrojo) to ES-DE

## Preview
| PS4 View | PS5 View | 
|----|----|
|<img width="1272" height="712" alt="ps4_cropped" src="https://github.com/user-attachments/assets/a62a5caf-8024-4a34-ae3e-e2114fd1d03a" />|<img width="1272" height="712" alt="ps5_cropped" src="https://github.com/user-attachments/assets/9fe35438-be23-4af2-a722-81e44886b3dc" />|





| 2D Carousel | 3D Carousel | Grid|
|----|----|----|
|<img width="1272" height="712" alt="2d carousel both_cropped" src="https://github.com/user-attachments/assets/c5642e93-566b-4b10-9fa9-b91bd6fda813" />|<img width="1272" height="712" alt="3d carousel both_cropped" src="https://github.com/user-attachments/assets/c27040e3-f2f2-45a6-b205-a846e85b57a4" />|<img width="1272" height="712" alt="grid_cropped" src="https://github.com/user-attachments/assets/5fb71773-d5f4-4ef5-8507-a2e25af1dae9" />|




## **Configuration Options**

- This theme has a simple set of options that can be changed directly from the UI Settings menu of ES-DE
  
- `Theme Variant` - sets the theme variant adjusting the gamelist view. 
   - `Carousel 2D - Detailed` - Gamelist view with a carousel using 2D box art and displaying miximage and description metadata
   - `Carousel 2D - Simple (Description)` - Gamelist view with a carousel using 2D box art and displaying description metadata
   - `Carousel 2D - Simple (Miximage)` - Gamelist view with a carousel using 2D box art and displaying miximage media and simple metadata
   - `Carousel 3D - Detailed` - Gamelist view with a carousel using 3D box art annd displaying miximage and description metadata
   - `Carousel 3D - Simple (Description)` - Gamelist view with a carousel using 3D box art and displaying description metadata
   - `Carousel 3D - Simple (Miximage)` - Gamelist view with a carousel using 3D box art and displaying miximage media and simple metadata
   - `Grid` - Gamelist view with a grid view with metadata

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
A custom color scheme lets you to modify the user avatar and username displayed in theme while also allowing you to continue to get updates from the theme downloader.

1) In the resources folder you will find a template file called [customizations.xml](https://github.com/RobZombie9043/playstation-x-es-de/blob/main/resources/customizations.xml)

2) Make a folder named `theme-customizations` and place a copy of the `customizations.xml` file inside that folder.  The folder structure should look like this when you are done:
   ```
   /ES-DE/themes/playstation-x-es-de/theme-customizations/customizations.xml
   ```

3) Edit the properites in `customizations.xml` to display your custom avatar and username. Some avatars have been included inside the `ES-DE/themes/playstation-x-es-de/resources/avatars` folder or you can add your own inside the `theme-customization` folder.
    
4) Set the `Theme Color Scheme` in ES-DE's UI Settings menu to `PS4 - Custom` or `PS5 - Custom` and you should see your custom avatar and username display.  If you see an error check that the paths discussed above are correct and then check that the values you added for each property are correct and well formatted.

## Credits

- Ported from the PlayStation-X ES theme by pajarorrojo - https://github.com/pajarorrojo/es-theme-PlayStation-X
- Many video assets from alpha-es-de by hplant6 - https://github.com/hplant6/alpha-es-de
- Some backgorund image artwork from slick-es-de by Weestuarty - https://github.com/Weestuarty-es-de/slick-es-de

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
