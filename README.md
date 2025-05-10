# pre2025cord

A theme for Discord that brings the pre-2025 refresh UI back without removing features

###### folders currently are not styled right so it might be weird for you

![Preview](Screenshot_1379.webp)

# Installation

## [Vencord](https://github.com/Vendicated/Vencord)

Paste the following in `Settings > Themes > Edit QuickCSS`:

```css
@import url("https://raw.githubusercontent.com/yes-0001/pre2025cord/refs/heads/main/src/main.css");
@import url("https://raw.githubusercontent.com/yes-0001/pre2025cord/refs/heads/main/src/addons/hide_nameplates.css");

/*  MAKE SURE TO CHECK GITHUB FOR ROOT UPDATES  */

:root {
	/*  transparency values [0.0-1.0] (type none to have no coloring added on), allows for use with a background image  */
	--transparency_call:              100%;  /*  discord call background  */
	--transparency_chat:              100%;
	--transparency_bg:                80%;
	--transparency_title:             40%;  /*  title (the thing above chat in servers, and the thing above the call bg in calls)  */
	--transparency_guildsList:        0%;  /*  server list  */
	--transparency_sidebarList:       100%;  /*  channel/dm list  */
	--transparency_panels:            0%;  /*  bottom left voice/user info  */
	--transparency_panels_streaming:  0%;  /*  bottom left streaming info  */

	/*  additive color values (the extra color added on top of the base theme color)  */
	--color_call:                     0, 0, 0;
	--color_chat:                     18, 18, 18;
	--color_bg:                       5, 5, 5;
	--color_title:                    0;
	--color_guildsList:               5, 5, 5;
	--color_sidebarList:              30, 30, 30;
	--color_panels:                   30, 30, 30;
	--color_panels_streaming:         30, 30, 30;
	
	/*  gradient values, looks best on transparent backgrounds  */
	--gradient_guildsList_point1:     94.2%;
	--gradient_guildsList_point2:     96%;

	/*  borders  */
	--call_border-bottom: 1px;
	--call_border-top: 1px;
	--sidebarList_border-right: 1px;
	--sidebarList_border-left: 1px;
	--sidebarList_border-top: 1px;
	--panels_border-left: 1px;
	--panels_border-top: 1px;

	/*  others  */
	--border_colors:               rgba(75, 75, 75, 0.5);
	--pill_padding:                  0px; /*  the white stuff to the left of guilds showing you: where you currently are, and what servers have unread messages  */
	--server_padding:                -4px; /*  padding for guild icons, change if they're too far left or right  */
}
```