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
// template index.html
<!DOCTYPE html>

<html>

<head>

  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <title>
    {% if page.title %}{{ page.title | escape }} - {{ site.title | escape }}
    {% else %}{{ site.title | escape }}{% endif %}
  </title>

  <meta name="description" content="{{ page.excerpt | default: site.description | strip_html | normalize_whitespace | truncate: 160 | escape }}">

  <link href='https://fonts.googleapis.com/css?family=Lora:400,700,400italic,700italic' rel='stylesheet' type='text/css'>
  <link href='https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800' rel='stylesheet' type='text/css'>

  <link rel="stylesheet" href="{{"/assets/vendor/bootstrap/css/bootstrap.min.css" | relative_url }}">

  <link rel="stylesheet" href="{{"/assets/vendor/fontawesome-free/css/all.min.css" | relative_url }}">

  <link rel="stylesheet" href="{{"/assets/main.css" | relative_url }}">
  <link rel="canonical" href="{{ page.url | replace:'index.html','' | absolute_url }}">
  <link rel="alternate" type="application/rss+xml" title="{{ site.title | escape }}" href="{{ "/feed.xml" | relative_url }}">

</head>

<body>
//  {% include navbar.html %}
//
//  {{ content }}
//
//  {% include footer.html %}
//
//  {% include scripts.html %}
//
//  {% include google-analytics.html %}
</body>

</html>

```

