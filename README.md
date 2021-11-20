# Matt Demers' Simple Slider Widget for StreamElements

I was annoyed at StreamElements' default "Row" widget, so I decided to make my own. It's a 500w x 100h animation that respects StreamElements' animations (I like slide in/out).

![Image](/demo.gif)

## Instructions for Install:

1. Enable custom CSS for your widget.
2. Add the contents of "demers-slider.css" to the CSS tab
3. Add the contents of "demers-slider.html" to the HTML tab
4. Add the contents of "demers-slider.json" to the Fields tab

## Instructions for Customization

**Important Note**: You **must** use the pickers and text field in the "Variables" menu, **not** the default StreamElements pickers. These will not work. 

```diff
- The sound dialog, however, WILL work.
```

![Image](/variables2.png)

Inside the variables menu, there are options for:

* Highlight color
* Background color
* Image
* Font Family
* Message text
* Text Alignment

**In text alignment**, if you want to add the Highlight color around anything, surround the word(s) with `<span class="highlight">TEXT</span>`. You must also include StreamElements' variables (see below)

### How to find StreamElements' variables

Usually in the alert you're editing, it'll show the valid variables at the top.

![Image](/variables.png)





