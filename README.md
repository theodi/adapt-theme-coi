# adapt-theme-coi

This theme is adapted from the ODI adapt theme to match the Caribbean Open Data Initiative

## Settings overview

This theme provides a maximum width theme that is responsive over mobile and desktop themes.

To use this theme here are a few tips.

Avoid content (e.g. text) in Articles and Blocks (set all the headings to a blank space ' '). Add content to components only.

The theme is ideally suited to alternative coloured blocks (one coloured, one white, one coloured etc)

It provides some Block classes (add these to the block) to control this:

Colors are outlined in the color-palette.png file.

Add to block (classes)

* inverted
	Inverts black on white text to white on colors
* color-{one,two,three,four,five,six,seven,eight,nine,ten}
	Controls the main color of block content. When inverted the background color will be this color and content will be white (or inverted color). When not used alongside inverted, the content will be this color. 
* footer inverted
	A dark color for the footer block
* section-banner
	Add this to a block to make a thin banner block and reduce top and bottom margins
	(used in ODI modules to split content from assessment)
