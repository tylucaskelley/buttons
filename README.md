# Buttons

by Ty-Lucas Kelley

---

I took the colors from [http://flatuicolors.com](http://flatuicolors.com) and made lots of nice buttons using Sass.

### Installation

Clone the repo:

    $ git clone https://github.com/tylucaskelley/buttons

and you can then use the Sass files (in the `scss` dir) or the compiled `main.css` file.

### Examples

See the [examples.html](https://cdn.rawgit.com/tylucaskelley/buttons/master/examples.html) file!

My [personal website](http://www.tylucaskelley.com) also utilizes these buttons and colors.

### Usage

I've set it up so you can use `a` tags:

    <a href='somewhere.over.the.rainbow'>
        <div class='carrot-circle-md'>hello</div>
    </a>

Or, you can use `button` tags:

    <button class='wet-asphalt-rect-xl'>hello</button>

The only thing you need to customize is the font!

### All Options

**Shapes**

* circle
* rect
* square

**Sizes**

* xs
* sm
* md
* lg
* xl

**Colors**

You can use any of these colors:

![colors](img/colors.png)

### To-do

* Break up things into smaller files
    *  people don't have to include one large CSS file in their project if they only want the red buttons / square buttons / etc.
