# Includer.js

A Javascript library for including other **HTML** files into one single **HTML** file.

### Get started

<br>

<b>📦 Installation</b><br><br>
You can use the CDN or download the [Javascript](https://cdn.hypll.org/services/programing/includerjs/includer.min.js) file.

CDN

```
https://unpkg.com/includerjs@1.0.3/dist/includer-1.0.3.bundle.js
```

<b>🚀 Usage</b><br>

Using the `<include>` tag.

Example:

```html
<include path="components/navbar.html"></include>
```

So in this example you see the `path` attribute. This is where your path to your html file is.

Root Example

```shell
components/
        └── navbar.html
index.html
```

## Logger

If you wan't to log messages, you can add the `includer-log="true"` attribute to the body tag

Example:

```html
<body includer-log="true">
  ....
</body>
```
