# Multiple Classes

An element can have multiple classes by listing each class
separated by a space.

---

### CSS
```CSS
.urgent {
  background: red;
}

.warning {
  font-family: monospace;
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
      This is my regular header.
    </h1>
    
    <h1 class="warning">
      This is my warning header.
    </h1>
    
    <h1 class="urgent">
      This is my urgent header.
    </h1>
    
    <h1 class="urgent warning">
      This is my urgent-warning header.
    </h1>
  </body>
</html>

```

---

### Example
![example](example.png)

