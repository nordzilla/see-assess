# ID Selectors

Rules can be specified for only elements that have a 
set ID by using id selectors. 

ID selectors are designated by a pound sign #. 

---

### CSS
```CSS
/* Matches specifically an h1 with this id. */
h1#first-header {
  color: blue;
}

/* Matches any element with this id. */
#second-header {
  color: red;
}


```

---

### HTML
```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1 id="first-header">
      I'm the first header.
    </h1>
    
    <h3 id="second-header">
      I'm the second header.
    </h1>
  </body>
</html>

```

---

### Example
![example](example.png)

