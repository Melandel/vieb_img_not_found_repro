Reproduction of a bug on the vieb browser (https://github.com/Jelmerro/Vieb/issues/530#issuecomment-1972951380)

## Bug reproduction
* using `vieb`, check `:version` is `11.0.0`
* using `cmd.exe`, type `vieb "markdownviewer:/C:\path\to\vieb_img_not_found_repro\foo\markdown.md"`

## Expected output
There are two pictures displayed

## Actual output
No picture is displayed

The html looks like that:

```html
<body id="markdownviewer" style="font-size: 14px; opacity: 1;"><h1>Some sexy markdown</h1>
<h2>Oh yeah</h2>
<p><img src="media/metro-montparnarsse.png" alt="">
<img src="media/arrondissements.jpg" alt=""></p>
</body>
```
