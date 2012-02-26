```
 _______ __          __         _____
|     __|  |_.--.--.|  |.-----.|     \.-----..----..----..-----.
|__     |   _|  |  ||  ||  -__||  --  |  _  ||  __||  __||  _  |
|_______|____|___  ||__||_____||_____/|_____||____||____||_____|
             |_____|
```

About
-----

StyleDocco takes your stylesheets and generates style guide documents with the stylesheets in question applied to the page.

`styledocco main.css` will generate `docs/main.html` with all the comments in the file (parsed through Markdown) in one column, and all the code in another column. The CSS in `main.css` will be applied to the page. To add extra styles to your documentation, add a file named `docs.css` in your `docs` folder.

If your project includes a `README` file, it will be used as the base for an `index.html`.

If you point StyleDocco to a directory, it will add a navigation between the different files.

StyleDocco will automatically compile any SASS, SCSS, Less or Stylus code before it is applied to the page.


Install
-------

`npm install styledocco`


Acknowledgements
----------------

Thanks to:

 * [jashkenas](https://github.com/jashkenas/docco)
 * [mbrevoort](https://github.com/mbrevoort/docco-husky)