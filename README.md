# Bootstrap 5 for Beginners

Starter code for using Bootstrap 5. Links and code are specific to version 5.2.0.

## Basic pages

*basic_page.html* – A copy of the Bootstrap “getting started” example using CDN links. Addition: One DIV element with the Bootstrap `container` class applied to it. This is an easy template to copy and use when you start a new page using Bootstrap.

*basic_page2.html* – Same as the previous example, but with a background color added to the container element so it’s easier to see how it changes at different browser widths.

## Rows and columns for layout

1. *rows_columns1.html* – Use of the `row` class and the simple `col` class (not responsive).

2. *rows_columns2.html* – Shows how use of the simple `col` class breaks the page on small screens.

3. *rows_columns3.html* – The alternative is to use *responsive* column classes, such as `col-md-3`, to adapt to screens of any size. **Compare this page in a narrow browser window or on a mobile device** to example 2 (above) to see why it‘s important to use the *responsive* column classes **instead of** the simple `col` class.

4. *rows_columns4.html* – Shows more specifically how to use *responsive* column classes correctly. Also shows how version 5 now makes it easy to **omit columns** and use new flexbox styles to **control spacing of elements across a row** — these classes are added to the element that has the `row` class.<br>
— *Responsive* column classes have this format: `col-md-2`<br>
— More than one *responsive* column class can be applied to one HTML element in this way: `class="col-xl-1 col-md-2"`

.
