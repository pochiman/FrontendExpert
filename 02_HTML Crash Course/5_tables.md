# 5 - Tables

Tables are best used to organize your page layout! 

Just kidding. Please don't ever use table layouts. This isn't 1996.

# Key Term

# <table> </>
  An HTML tag for representing data with rows and columns. As a general rule,
  anything that could go in a spreadsheet probably also makes sense in a <table>

  There are a variety of tags associated with tables, with these being some of the
  most common:

  • <tr>: A single row in the table.

  • <th>: A heading in the table. This should be used with the `scope` attribute 
  of either `row` or `col` to choose what the content is a heading for.
  
  • <td>: A single piece of data in the table, also referred to as a cell.

  • <thead>: A grouping tag for the heading of a table, usually
    containing a single <tr> with column headings.

  • <tbody>: A grouping tag for the body of the table, used for
    containing the primary rows of data.

  • <tfoot>: A grouping tag for the footer of the table.

  • <caption>: A caption or title for the table.
  
  For example, this is a valid HTML table:

  <table>
    <caption>AlgoExpert Products</caption>
    <thead>
      <tr>
        <th scope="col">Product</th>
        <th scope="col">Rating</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">AlgoExpert</th>
        <td>5</td>
      </tr>
      <tr>
        <th scope="row">SystemsExpert</th>
        <td>5</td>
      </tr>
    </tbody>
  </table>

  Learn more: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table  
