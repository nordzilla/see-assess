# General Class Selectors

Rules can be specified for all elements that have a given class
by adding a CSS rule that starts with a dot.

---

### CSS
```CSS
/* Applies to all elements that have the warning class */
.warning {
  font-family: monospace;
}

/* Applies to only <h3> elements that have the warning class */
h3.warning {
  color: blue;
  background: red;
}

/* Applies to only <p> elements that have the warning class */
p.warning {
  color: red;
  background: blue;
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
    <h1>
      These are my regular things.
    </h1>
    
    <h3>
      Regular header.
    </h3>
    
    <p>
      Regular paragraph.
    </p>
    
    <h1>
      These are my warnings
    </h1>
    
    <h3 class="warning">
      Header warning.
    </h3>
    
    <p class="warning">
      Paragraph warning.
    </p>
  </body>
</html>

```

---

### Example
![example](example.png)

