# sd-webui-textstyles

preprocessing for controlnet textstyles

- preprocessing for controlnet textstyles extention for [AUTOMATIC1111's stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) 

This script allows you to easily generate PNG files for every letter in a word for batch processing in Stable Diffusion. 

Similar to Adobe's last release of Text Styles, this script can help you achieve style effects on your text without having to make seperate png's. 
(you will have to postprocess the images after generating to make the words whole again with an image editor.)


I recommend using ControlNet HED to get the edges of the letters and an image size of 1024px to get better quality, adjust the settings to get different effects.


# **Features:**

* Supports your own font .otf/.ttf files

* Allows you to control the size of the generated PNG files

* Enables you to adjust the colors of the letters and background

* Supports the use of images as overlays to put over the letters and/or background

* takes under a second to process and export the png's


### Install

1. Open "Extensions" tab.
2. Open "Install from URL" tab in the tab.
3. Enter `https://github.com/nicolai256/sd-webui-textstyles.git` to "URL for extension's git repository".
4. Press "Install" button.
5. Wait 5 seconds, and you will see the message "Installed into stable-diffusion-webui\extensions\sd-webui-controlnet. Use Installed tab to restart".
6. Go to "Installed" tab, click "Check for updates", and then click "Apply and restart UI". (The next time you can also use this method to update ControlNet.)
7. Completely restart A1111 webui including your terminal. (If you do not know what is a "terminal", you can reboot your computer: turn your computer off and turn it on again.)


#### **Feel free to do a pull request or open an issue if you have any suggestions for additional features or improvements.**

![xy_grid-0006-2934360860 0](https://user-images.githubusercontent.com/122196982/214343111-e82bb20a-799b-4026-8e3c-dd36e26841e3.jpg)
