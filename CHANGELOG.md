# Changelog

### 1.4.5
- Add style for reader and narrator components

### 1.4.4
- Only use white audio indicator when using a lightweight theme

### 1.4.3
- Add tab audio indicator (for Pale Moon 28.3+)
- Remove remnants of web apps
- Minor adjustments to in-content style

### 1.4.2
- Additional fixes
	- Fix all tabs button appearance (no thumbnails/list mode)
	- Change .toolbarbutton-badge-container to .toolbarbutton-badge-stack
	- Add more buttons to the exclusions to arbitrary toolbar icon size
	- Add --toolbar-border-radius variable
	- Add --tab-selected-highlight variable
	- Adjust default toolbar color for Win7 + non-default theme/other platforms (use FF4 default)
	- Some selectors did not use var counterparts
- Use unprefixed form of these properties
	- -moz-margin-start -> margin-inline-start
	- -moz-margin-end -> margin-inline-end
	- -moz-padding-start -> margin-padding-start
	- -moz-padding-end -> margin-padding-end

### 1.4.1
- Drop support for Pale Moon 27
- Adjust site icon glow on identity box
- Change the padlock color to plain white on secure sites
- Make the transition between the tab and the navigation bar smooth (it looks abrupt)
- Fix inconsistent site icons in Saved Logins
- Update developer tools (in browser.css), media controls, menu, and Permissions Manager style
- Use CSS variables in browser style
  - Toolbar button transition speed and timing function, toolbar color, toolbar button radius, and tab background can now be adjusted

### 1.4.0
- Initial support for Pale Moon 28

### 1.3.0
- Default accent color on Win10 changed to black-on-white
- Remove unused urlbar progress bar styles (as of PM 27.5)
  - This causes problems with the status bar progress meter

### 1.2.9
- Drop support for PM 27.4 and lower
- Support PM 27.5's Win10 window styling implementation
- Styling for verify places database (about:support)
- Restore app menu private browsing indicator
- Restore padlock icons and add glow to padlock and favicon
  - If you want to remove the padlock, set the **browser.padlock.show** pref to false.

### 1.2.8
- Drop support for versions lower than PM27.4
- Update devtools styling

### 1.2.7
- Restore missing icons on notification panel

### 1.2.6
- Remove aboutReader.css
- Update session restore and certificate error styling
- Minor fixes to browser.css (see commit)
- Don't invert toolbar buttons dropmarker when tabs are on top

### 1.2.5
- Proper styling for bookmark items and identity icon
- Remove border from proxy favicon (default)
- Add image document proxy favicon styling
- Add missing glow to some toolbar icons
- Proper standalone go-button styling
- Minor changes to add-ons page style
- Restore in-content ui background
- Remove unused images
	
### 1.2.0
- Fix inconsistent styling
- Restore missing opacity applied to buttons when it is disabled during full/text modes
- Restore glow on the forward button
- Use defined color instead of ThreeDDarkShadow for urlbar border color
- Made the identity box round again when a notification popup box is visible
- Add support for Home Styler (when you have this add-on, the about:home page will now look like FF4's)

### 1.1.5
- Fix for margin on text-only mode when use small icons is not enabled
- Restore missing background for unselected tabs
- Add a 1px margin near the back button
- Add style to search textbox and buttons in add-ons page

### 1.1.0
- Fix for abrupt animation end on toolbar button
- Add missing rounded right edges of urlbar go/stop/reload
- Style toolbar buttons for other modes in main browser

### 1.0.0 - 2017-02-16
- Initial release