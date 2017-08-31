# ---Sublime V0.1 Beta Release---

----------

## Sublime.css is a free framework to help out with building websites. It is style-agnostic, containing only the code you need, and none that you don't. Sublime.css is intended to make life eaiser for anyone developing websites, and it lets you choose the styling for your particular needs. If you do need styling specifically for Sublime.css, style packs are planned for the near future.

----------

### Once you have the "Sublime" folder in your project folder, simply link to "Sublime.css" in the head of your document with a <link> element.

### Make sure that you place the link for Sublime above your own stylesheets, so that the styles you have applied override those in Sublime.css.

----------

### Sublime.css can do three main things: (As this version of sublime is only in beta, only headers and a limited amount of buttons are supported, however foward compatibility will be maintained with later editions.)

    
    > Buttons
    > Headers (Not Currently avalible)
    > Grids

### Using Sublime is simple: just add the apropriate classes to html elements, for example:

`<a href="https://yoursite.com/whatever" class="Sublime-warningBtn" >Hello, World!</a>`

### The above code will create an anchor with styling for a warning button.

### See below for a list of all classes available with Sublime.css



#### Grid Row
```
sublime-gridWrapper
```


##### Grid columns- the numbers on the end are the fraction of the container that the grid column takes up

```
sublime-grid-1-15

sublime-grid-2-15

sublime-grid-3-15

sublime-grid-4-15

sublime-grid-5-15

sublime-grid-6-15

sublime-grid-7-15

sublime-grid-8-15

sublime-grid-9-15

sublime-grid-10-15

sublime-grid-11-15

sublime-grid-12-15

sublime-grid-13-15

sublime-grid-14-15

sublime-grid-15-15
```

#### Buttons
```
sublime-yesBtn is a affirmitive button.

sublime-noBtn is a negitive button.

sublime-warningBtn is a warning button.

sublime-greyBtn is a simple grey button.


###Notes:

####Grid items can be reordered with
```
.sublime-grid-whatever-your-grid-item-is
{
  -webkit-order: (interger here); /* For Safari */
  order:         (interger here);
}
```
without changing the structure of the html.


#*Sublime.css is licenced under the MIT licence.*
