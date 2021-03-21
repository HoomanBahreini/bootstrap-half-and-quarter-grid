# bootstrap-half-and-quarter-grid
This project allows you to use half/quarter columns using **Bootstrap 4** grid system. The new classes are:

````
/* replace star with a number between 0 and 11 */
col-*-1qtr 
col-*-half
col-*-3qtr
````
So if you want to have a 0.5 column, you can use `col-0-half` class and if you want to have 3.75 column you can use `col-3-3qtr` class. 

Also note that you can use responsive classes, such as:

1. `col-sm-2-half` (2.5)
2. `col-md-0-3qtr` (0.75)
3. `col-lg-11-1qtr` (11.25) 
4. `col-xl-5-half` (5.5)


Example:
--------

The following example devide the screen in 2 columns with half and quarter fractions of standard grid system:

````
// add a reference to: https://cdn.jsdelivr.net/gh/hoomanbahreini/bootstrap-half-and-quarter-grid/fractional-grid.min.css
<div class="container">
  <h2>Using fraction of columns</h2>
  <div class="row">
    <div class="col-2-3qtr bg-success">col-2-3qtr (2.75)</div>
    <div class="col-3-1qtr bg-warning">col-3-1qtr (3.25)</div>
    <div class="col-3-half bg-success">col-3-half (3.5)</div>
    <div class="col-2-half bg-warning">col-2-half (2.5)</div>
  </div>
</div>
````

Usage:
------

If you want to use the file from an existing CDN, you can use one of the following:

https://cdn.jsdelivr.net/gh/hoomanbahreini/bootstrap-half-and-quarter-grid/fractional-grid.css
https://cdn.jsdelivr.net/gh/hoomanbahreini/bootstrap-half-and-quarter-grid/fractional-grid.min.css

or you can copy-paste the entire css in your own project.
