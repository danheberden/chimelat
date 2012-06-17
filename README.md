# ChimeLat - a pretty neat LimeChat theme

So, yeah, it's my limechat theme. Besides looking pretty neat, it does
these nifty things:

* users get one out of 16 colors and retain that color through the chat
* channels in the log get that same feature

This makes it way easier to use the all channels log, not to mention
viewing the channel log.

It also has log functions 'n stuff. I was able to hit the ground running
on how the hell to do any of this thanks to Ryan Florence and his
limechat limescrips. [Check them out](https://github.com/rpflorence/limescripts). 

## Installation:

Clone the theme into your Limechat themes folder. Below is the default but in
case it isn't there, open LimeChat's preferences, go to the Theme tab, and _Open in Finder_.

```shell
cd ~/Library/"Application Support"/LimeChat/Themes
git clone git://github.com/danheberden/chimelat.git

# set up symlinks so theme is visible 
ln -s chimelat/ChimeLat.yaml ChimeLat.yaml
ln -s chimelat/ChimeLat.css ChimeLat.css
ln -s chimelat/ChimeLat.js ChimeLat.js
```

Then open preferences and then you can select the theme.

## Screenshot:

![](http://danheberden.com/share/79777e5.png)

<3z
