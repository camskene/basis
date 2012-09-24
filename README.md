BasisCSS
=============

A responsive 24 column grid with some type styles.

What does it do?
-----------

* Divides your page into 24 columns with 20px gutters
* Builds on top of [normalize.css](https://github.com/necolas/normalize.css) to provide some type styles.
* Includes a PSD template to work from

How to use it
-----------
Link to grid24.css if you just want a responsive grid or link to grid24.css, [normalize.css](https://github.com/necolas/normalize.css) and basis.css for type styles and responsive images.

The columns are set in percentages and the outer most div with a class of .row has been given a max-width of 1200px: 1200/24 = 50.
You can specify any max-width you want on the outer most row, I just used 1200 as it gave me a nice round number of 50.

Columns have 10px padding on the left and the right giving you 20px gutters.

Your HTML should something like this:

    <body>
        <div class="row">
            <div class="sixteen columns">
                <p>Primary content would go here.</p>
            </div>
            <div class="eight columns">
                <p>Sidebar would go here.</p>
            </div>
        </div>
    </body>

Browser support
-----------

Any browser that supports box-sizing: border-box.

* Google Chrome
* Mozilla Firefox 3+
* Apple Safari 4+
* Opera 10+
* Internet Explorer 8+

If you need IE7 support you can use the grid-alt.css file, it uses margins to create gutters between the columns and doesn't use box-sizing.

License
-----------

Public domain

Acknowledgements
------------
Thanks to the excellent work of these projects:
* [zurb/foundation](https://github.com/zurb/foundation)
* [Digital Surgeons Gumby Framework](https://github.com/dsurgeons/Gumby)
* [normalize.css](https://github.com/necolas/normalize.css)
* [html5 boilerplate](https://github.com/h5bp/html5-boilerplate)








