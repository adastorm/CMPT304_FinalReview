# CMPT 304 SHEEEET -- Jonah Watts & Judah Starkey

---

#### HTML

Default structure of

---

#### CSS

- Class `.class`

- Defualt Property `html` or `h1`

- ID selector `#id`

- On Hover Property `#front:hover`

Some Basic Selectors

```css
.footer {
    color: rgb (225, 224, 224);
    padding: 10px 10% 10in 50px;
    text-align: center;
    left: 10px; /*Use in the pacman lab to move pacman*/
}
```

---

#### Java Script

---

#### Jquery

The jQuery syntax is tailor-made for selecting HTML elements and performing some action on the element(s).

Basic syntax is:

- `$(selector).action()`

- A `$` sign to define/access jQuery

- A `(selector)` to "query (or find)" HTML elements

- A jQuery `action()` to be performed on the element(s)
  Examples:

```js
$(this).hide(); // hides the current element.
$("p").hide(); // hides all <p> elements.
$(".test").hide(); // hides all elements with class="test".
$("#test").hide(); // hides the element with id="test".

$(document).ready(function () {
    // Hides an elemetn when a user clicks on teh button
    $("button").click(function () {
        $(".test").hide(); // Change with .test or p
    });
});
```

---

#### PHP

---

#### MySQL

---

Exit a query

- ```sql
  \c
  ```

How to add a book to the database

- ```sql
  INSERT INTO books VALL
  ```

Show all of the data from inside of the database

- ```sql
  SELECT * FROM books
  SELECT title, price FROM books
  ```

Method to show the use of the different keys in the table. When inserting duplicate data this will show you if there is duplicate data in the table.

- ```sql
  describe books
  ```

Method to update or delete an entry in a database

- ```sql
  DELETE FROM books WHERE ISBN = 4;
  SELECT * FROM books WHERE Price <= 19;
  ```

How to edit an entry from the table

- ```sql
  UPDATE books SET Title = 'REPLECEMENT' WHERE ISBN = 'xxx-xxx-xxx';
  ```

How to alter the type iside a table

- ```sql
    modify collumn Price decimal(6,2);
  ```
  
  In this example using decimal wrather than a floatng point will lead you to have an exact number wrather than the floating point

- When inserting into the database, make sure to insert the data in order and to provide quotations around string and none around floats

- Also when entering a thing above the limit, it trunkates the limit
