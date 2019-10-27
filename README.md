### vex
---
https://github.com/HubSpot/vex

```js
// src/vex.js

var escapeHtml = function escapeHtml (str) {
  if (typeof str !== 'undefined') {
    var div = document.createElement('div')
    div.appendChild(document.createTextNode(str))
    return div.innerHTML
  } else {
    return ''
  }
}


```

```
```

```
```

