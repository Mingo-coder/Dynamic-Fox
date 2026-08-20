# ~~Elegant-Floorp~~ Dynamic Fox 
feel free to open issue on any topic.
This is a simple userChrome.css file to make Waterfox Browser elegant and more compact than the given compact mode.

In the Customize Toolbar settings I dragged bookmark bar to the right side of url bar and enabled compact mode in Density tab located at the bottom

I need to document all the other changes I made in about:flags eventually.
It's easier to install tabliss extension but clutters the URL bar for me 
Go to the url bar and type about:flags 
so I set the flag: 

browser.startup.homepage = https://web.tabliss.io/
floorp.newtab.overrides.newtaburl = https://web.tabliss.io/
browser.taskbarTabs.enabled = False

Waterfox needs a restart after this flag has been set to apply the effect.

## Screenshots
### Dark Mode
<img width="1802" height="1038" alt="image" src="https://github.com/user-attachments/assets/8fe69327-88e6-4cfe-a6f4-009bf39bac5c" />


### Light Mode
<img width="95" height="29" alt="image" src="https://github.com/user-attachments/assets/dfe5fdfe-ca8e-4460-a734-150dd82780d0" />

The codes were modified from https://github.com/datguypiko/Firefox-Mod-Blur
I made this for personal use but turned out quite useful so I hope it's ok with the original author of the theme.
