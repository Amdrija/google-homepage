# Google Homepage Recreation using HTML and CSS

## Introduction
Here I'm trying to recreate the google homepage as an assignment from the Odin Project. 

This was done only with HTML and CSS, I have used only font-awesome JS for icons, but apart from that there was no JS involved in this project. You can visit it at https://amdrija.github.io/google-homepage/.

## Possible issues

I've tried my best to replicate Google's homepage, but there are still some things I haven't been able to do. Namely, in order to include the search and keyboard icon in the textbox, I have enclosed them into a div like this:

```html
<div class="search-box">
    <i class="fas fa-search"></i>
    <input type="text" name="search" id="search">
    <i class="far fa-keyboard"></i>
</div>

```

Then I styled the searchbox to look like the Google's search box. When you hover over the searchbox, it gets a box shadow. Now the problem is that I can't apply that shadow when the textbox is focused, because it is a child of the search box and there were no parent css selectors at the time of making this project. This would be possible to overcome if I use JavaScript, but that was not the point of this project.

