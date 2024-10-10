### 1. Simple PHP Program to Print Your BIODATA on the Browser Screen



```php
<?php
// Define biodata variables
$name = "Aster Dev";
$age = 25;
$address = "1234 Elm Street, City, Country";
$phone = "123-456-7890";
$email = "asterdev@example.com";

// Display biodata
echo "<h1>Biodata</h1>";
echo "<p><strong>Name:</strong> $name</p>";
echo "<p><strong>Age:</strong> $age</p>";
echo "<p><strong>Address:</strong> $address</p>";
echo "<p><strong>Phone:</strong> $phone</p>";
echo "<p><strong>Email:</strong> $email</p>";
?>
```


---

### 2. Error(s) in the Code Below

```php
<?php 
 / This is a comment for PHPprogram 
 echo "Display first line </br>";
 echo "Display second line </br> "
 Print "Display third line with print statement ";
?>
```

#### Errors:
1. The comment syntax is incorrect. In PHP, single-line comments should use either `//` or `#`, not `/`.
2. There is a missing semicolon (`;`) at the end of the second `echo` statement.
3. The `Print` statement should be written in lowercase as `print` (PHP is case-sensitive).

---

### 3. Correct Code

```php
<?php 
 // This is a comment for PHP program
 echo "Display first line </br>";
 echo "Display second line </br>"; // Added semicolon
 print "Display third line with print statement </br>"; // Corrected the print statement
?>
```

---

### 4. Output of the Above Code

The corrected code will produce the following output:

```
Display first line
Display second line
Display third line with print statement
```

Each line will be displayed on a new line due to the `</br>` (line break) tags.

---

### 5. PHP Code to Display Text Using HTML Formatting Tags in `echo` Statements

Here’s an example PHP code that uses HTML formatting tags within the `echo` statement:

```php
<?php
// Display text with HTML formatting
echo "<h1>Welcome to My Website</h1>";
echo "<p>This is a paragraph with <strong>bold</strong> text and <em>italicized</em> text.</p>";
echo "<ul>";
echo "<li>Item 1</li>";
echo "<li>Item 2</li>";
echo "<li>Item 3</li>";
echo "</ul>";
?>
```

This code will render a heading, a paragraph with bold and italic text, and an unordered list on the browser.
