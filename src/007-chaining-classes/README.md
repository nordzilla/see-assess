# Chaining Classes

Classes can be chained in CSS to specify rules only
for elements that have all of the classes in the chain.

Each class added to the chain is separated by a dot.

---

### CSS
```CSS
.urgent {
  background: red;
}

.warning {
  font-family: monospace;
}

.urgent.warning {
  color: blue;
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

