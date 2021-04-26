# Icon Captcha for PHP
Inspired from [fabianwennink's icon captcha](https://github.com/fabianwennink/IconCaptcha-Plugin-jQuery-PHP). Although fabianwennink's icon captcha works nicely, there was some modifications to be made. The modifications are listed below:
* Starting with not capping the icon amount, automatically calculating how many icons are there in the user's set folder.
* Instead of having just 1 icon that needs to be selected, I modified it to have 2.
* Instead of requesting each icon separately, we generate a sprite so that the front-end only needs to load the icons once.
* Made noise of the icon more controllable, instead of it being capped to a limited amount (which was originally 50).
* Addon is now more static website focused, meaning it's easier to integrate into websites that do not use JavaScript.

## To-Do
* Remove flex styling to support older browsers
* Make the amount of icon's modifiable
* Automatically generatable captcha, instead of c+p the current code in.

## Preview
![alt text](https://raw.githubusercontent.com/Cryptofer/icon-captcha/main/preview.png "Preview")
