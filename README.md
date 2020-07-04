### Bootstrap 4 Four Column Portfolio Layout | snippets9
---



[RESULT](https://jsfiddle.net/StartBootstrap/42bgwce1/)

#### CDN
[jquery.slim.min.js 3.3.1](https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.slim.min.js)
[bootstrap.min.css 4.4.1](https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css)
[bootstrap.bundle.min.js](https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.bundle.min.js)

```
// asset
jquery.slim.min.js
bootstrap.min.css
bootstrap.bundle.min.js
```

```
<!DOCTYPE html>

<html>

{% include head.html %}

<body>

  {% include navbar.html %}

  {{ content }}

  {% include footer.html %}

  {% include scripts.html %}

  {% include google-analytics.html %}

</body>

</html>

```

