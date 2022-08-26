# Bootstrap 5 for Beginners

Starter code for using Bootstrap 5. Links and code are specific to version 5.2.0.

[Live versions of these pages are here.](https://macloo.github.io/bootstrap5-beginners/)

Here are descriptions of the files in this repo:

## Basic pages

1. *basic_page.html* – A copy of the Bootstrap “getting started” example using CDN links. Addition: One DIV element with the Bootstrap `container` class applied to it. **This is an easy template to copy** and use when you start a new page using Bootstrap.

2. *basic_page2.html* – Same as the previous example, but with a background color added to the container element so it’s easier to see how it changes at different browser widths.

## Rows and columns for layout

1. *rows_columns1.html* – Use of the `row` class and the simple `col` class (not responsive).

2. *rows_columns2.html* – Shows how use of the simple `col` class breaks the page on small screens.

3. *rows_columns3.html* – The alternative is to use *responsive* column classes, such as `col-md-3`, to adapt to screens of any size. **Compare this page in a narrow browser window or on a mobile device** to example 2 (above) to see why it‘s important to use the *responsive* column classes **instead of** the simple `col` class.

4. *rows_columns4.html* – Shows more specifically how to use *responsive* column classes correctly. Also shows how version 5 now makes it easy to **omit columns** and use new flexbox styles to **control spacing of elements across a row** — these classes are added to the element that has the `row` class.<br>
— *Responsive* column classes have this format: `col-md-2`<br>
— More than one *responsive* column class can be applied to one HTML element in this way: `class="col-xl-1 col-md-2"`

**NOTE** that rows (elements that have the `row` class) are essential when you use columns. Group the column elements inside a row element. Use as many separate row elements as you need. Rows are independent of one another and can be styled quite differently from one another.

```
row 1
column  column  column

row 2
column  column

row 3
column  column  column  column  column
```

Columns can be wide or narrow. The maximum number of columns in any one row is 12. *rows_columns4.html* shows a row with 12 columns.

## Google fonts, responsive images, Bootstrap buttons

1. *goog_fonts.html* — How to add Google fonts to your Bootstrap pages, replacing the default Bootstrap fonts.

2. *images.html* — Responsive images in Bootstrap are easy, adding one class inside the IMG tag.

3. How to use the Bootstrap button styles.

.
