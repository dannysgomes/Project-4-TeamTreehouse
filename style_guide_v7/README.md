# Using nested keys in scss variables
- Use map-get to grab a variable and a particular 'key' from that variable

```
.nav-link:hover {
    color: $text-white;
    background-color: map-get($map: $btn-colors, $key: warning);
  }
```