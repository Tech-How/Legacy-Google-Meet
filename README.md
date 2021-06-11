---
### *Big update coming soon to fix inaccurate coloring, and bring back the old chat/people/background/activities menus without rounded corners! Stay tuned!*
---
# Legacy Google Meet Project

<img src="https://i.ibb.co/qMRNy8g/old-google-meet-colors.png"/>

Google is ditching the well-loved classic design of its Meet product. But I wasn't just going to sit there and watch it go by. I gathered some tools, hopped on Userstyles.org, and designed a skin to bring back the classic style Google Meet. It's currently very early in development, and constantly being worked on. Try it out and let me know what you think!

**[Install with Stylish extension](https://userstyles.org/styles/205419)** | [Open a new issue/feature request](https://github.com/Tech-How/Legacy-Google-Meet/issues/new/choose) | [Send feedback via email](mailto:tech_how_youtuber_55@yahoo.com?subject=Old%20Google%20Meet%20Feedback) | [Get update notifications](https://forms.gle/xRP86G4FBPVX3quq5)

[View release notes & CSS code](https://github.com/Tech-How/Legacy-Google-Meet/releases)

## Known Issues
--Text on Google Meet homepage 'New Meeting' button missing

--Text on 'Something went wrong' 'Rejoin' button missing

-----(These missing items are due to the fact that the text on those buttons reuses the same class name. So I had to pick and choose, and I decided that it made more sense to ensure the buttons and text inside of the actual meeting were visible.

--Polls, breakout rooms, Q&A, and other G Suite only colors are still blue. Sadly, I do not have my own G Suite account, so I don't have access to the necessary tools to convert the CSS code for those elements :(

--Captions and Troubleshooter button in menu remains green, because Google reuses classes from the Activities and Add people button

--Change layout menu is still blue

--Graphs in 'Troubleshooting & help' section are still blue (I've looked forever and can't find the class associated with the graphs! If you have an idea, lemme know!)

--'Raise hand' button green instead of white on G Suite accounts, again, Google reusing classes :/

--No rounded corners on bottom-left meet popups captions and such, they vanish too quickly for me to inspect further.

--Some icons that are usually white now display green

--Meeting name appears slightly faint in the 'Meeting details' pane

## Manual Installation Instructions
If [Userstyles.org](https://userstyles.org) isn't working for you, you can install the skin manually.

1. Install the Stylish *[extension](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe)* (or any manager of your choosing, although instructions may vary.)
2. Right-click on the extension, and open the options page.
3. Click 'Write new style'
4. Enter a name for the style.
5. Navigate to the [releases page,](https://github.com/Tech-How/Legacy-Google-Meet/releases) and scroll down to download the 'theme.css' file.
6. Copy the CSS code into the new style.
7. At the bottom of the code box, click 'Specify'. Select *'URLs on the domain'* and enter *'meet.google.com'.*
8. Click the Save button near the left of the screen.

---
**This theme may not be copied and/or redistributed in any way, shape or form.**
