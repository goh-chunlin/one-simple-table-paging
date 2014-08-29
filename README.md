one-simple-table-paging
=======================

A small piece of JS code which does simple table pagination.

![OneSimpleTablePaging](image/OneSimpleTablePagingPoster.png?raw=true)

## Project Description

Unlike most of the other solutions which require a lot of CSS files and images, this project aims to provide an alternative by just doing all the table pagination in one JS file without using any image. Users just need to put in one JS file in their project to have a simple table pagination setup for them.

## How to Use

In this section, we will show how OneSimpleTablePaging is applied to an existing HTML table which has id "main-table".

To keep it simple, OneSimpleTablePaging only has two things for the users to configure.

 * Simplest case:
   * *$('#main-table').oneSimpleTablePagination({});*
 * Set the number of rows per page, for example 20 rows per page:
   * *$('#main-table').oneSimpleTablePagination({rowsPerPage: 20});*
 * Set the position of the pagination bar (can be either on top or bottom of the table):
   * *$('#main-table').oneSimpleTablePagination({topNav: true});*
   * The code above will have the pagination bar positioned on top of the table.

By default, rowsPerPage is 10 and topNav is false.

## Requirement

 * jQuery Version 1.7.1 or above

## Other Information

The code in this project is based on Ryan Zielke's tablePagination (http://neoalchemy.org/tablePagination.html) which is licensed under the MIT licenses: http://www.opensource.org/licenses/mit-license.php. Button designs are based on Google+ Buttons in CSS design from Pixify (http://pixify.com/blog/use-google-plus-to-improve-your-ui/).

You can read more about this project at my blog: http://cuteprogramming.wordpress.com/2012/04/07/259/
