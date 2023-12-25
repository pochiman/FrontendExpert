# Item Cart

Implement an item cart in HTML with the following static data:

+----------+-----------+--------------+
|   Item   |   Price   |   Quantity   |
|----------+-----------+--------------|
|  Banana  | $1.00     | 3            |
|  Burger  | $6.90     | 1            |
|  Cookie  | $4.20     | 4            |
|----------+-----------+--------------|
|  Total   | $12.10    | 8            |
+----------+-----------+--------------+

Your HTML code should use a table with proper semantic markup and with `Item Cart` 
as its caption.
  
You only need to write the HTML that would go inside of a document's <body> tag; 
no need to worry about the <head> tag, the <html> tag, or the `<!DOCTYPE>` declaration. 

# Hints

# [Hint_1]
These table related tags might be useful: `table`, `thead`, `tbody`, `tfoot`, `tr`, 
`th`, `td` and `caption`.

# [Hint_2]
The column headers should be considered their own row, only using `th` tags rather 
than `td` tags.

# [Hint_3]
Row headers, such as the "Banana" header should also use the `th` tag. However they 
should be differentiated from column headers by using the `scope` attribute.
