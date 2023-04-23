# Widescreen-Arcade-Controls-Information-Images
**tldr: This is for those that has additional sub-display with non-conventional aspect ratio (e.g. 3.73) and NOT 16:9 or 4:3 or 21:9 and wishes to display control information such as moveset for fighting games.**

Here you can find my curated widescreen images reordered to display relevant control information on sub-display with aspect ratio 3.73 (1920x515) or similar. The file structure here follows the same structure that Launchbox used to store such image type.

# Requirements
You had to first install [MultiMonitor](https://forums.launchbox-app.com/files/file/3892-launchbox-multi-monitor-and-bigbox-3rd-monitor-plugin/)  plugins for Launchbox. Then configure your second or third display to show `Game Controls` so that it will read the game control information for the selected game.

![](https://i.imgur.com/vmi6tIt.png)


# Motivation
The pictures scraped by Launchbox Games DB already contains multiple images for controls information for Arcade game stored in `Arcade - Controls Information`. However the aspect ratio is mixed and most of them (4:3) are not suitable to display on a sub-display (e.g. marquee display) with aspect ratio fo 3.73 or similar. Otherwise the text might look too small and the black side borders are too much. 

As of present Launchbox still doesn't allowing user to select a default image for an image types with multiple images. It always display the first image with the smallest number, e.g. `-01` or if multiple images are found. There is no option to modify the order such as random.

# Monitor Display
The images here are best viewed with a screen with aspect ratio of 3.73 (e.g. 1920x515) that is typical in most sub-display to show marquee, such as the NV126B5M-N42. You may easily find them on Taobao https://world.taobao.com/item/680221506574.htm?.

![](https://i.imgur.com/9FX9g1e.png)


Picture of me mounting the NV126B5M-N42 LCD display to my Vewlix/Chewlix player panel. The spot used to be a white LED strip.

![](https://i.imgur.com/GFk8pUI.jpg)

The text on the moveset is also visible clearly with the LCD size.
![](https://i.imgur.com/3Tusqb4.jpg)



# Method
I browse through the image scraped by Launchbox, and simply copy and rename the control information images that best list a moveset for an arcade game to `-00`. Since Launchbox always choses image with the smallest index number, it will use it instead of the different `-01` image name that might contain 4:3 or 16:9 aspect ratio not ideal to be displayed on the sub-display. 

The image were scraped on my **full merged MAME 0.250 set**.

# How to Use
Simply copy and paste all those images with `*00.jpg` and `*00.png` into your `LaunchBox\Images\Arcade\Arcade - Controls Information` folder.

# TODO
- Find more high quality images for more arcade games.

# EOF