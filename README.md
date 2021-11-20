# Matt Demers' Simple Slider Widget for StreamElements

I was annoyed at StreamElements' default "Row" widget, so I decided to make my own.

## Instructions for Install:

1. Enable custom CSS for your widget.
2. Add the contents of "demers-slider.css" to the CSS tab
3. Add the contents of "demers-slider.html" to the HTML tab
4. Add the contents of "demers-slider.json" to the Fields tab

## Instructions for Customization

**Important Note**: You **must** use the pickers in the "Variables" menu, **not** the default StreamElements pickers. These will not work.

### Images

Under "variables" there's an image picker

### Highlight color

Under "variables" there's a color picker

### Font

Under "variables" there's a Google Font picker

### Message

Under "variables" there's a message selector. If you'd like to change the message, change it in "demers-slider.json". **Be mindful to keep the \s in the HTML for the highlight color. They need to be before the double quotes before/after "highlight color"**.

`
"<span class=\"highlight-color\">{name}</span> just subscribed!": "New Subscriber"`

If you want to keep "name" the highlight color, copy `<span class=\"highlight-color\">{name}</span>` together to keep it like that. You can also surround any other word with `<span class=\"highlight-color\">WORDGOESHERE</span>` to apply the highlight color.


## How to add your own highlight color

Change the hex code in the .html file (see comments in the file)

## How to find StreamElements' variables

In each 

![Image](/alertvariables.png)



