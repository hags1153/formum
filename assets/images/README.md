# Images

Drop her photos in here. Recommended:

- JPEG or WebP, ~1600px on the long side
- Filenames lowercase-with-dashes: `mum-beach-2018.jpg`, `young-jeneen.jpg`, etc.

To use one in the gallery, edit `index.html`, find a placeholder figure that
looks like:

```html
<figure class="gallery__item placeholder">
    <div class="placeholder__inner"><span>photo</span></div>
    <figcaption>caption goes here</figcaption>
</figure>
```

…and replace it with:

```html
<figure class="gallery__item">
    <img src="assets/images/mum-beach-2018.jpg" alt="Mum on the beach, 2018" />
    <figcaption>Florida, the year you decided.</figcaption>
</figure>
```

Sizes available as modifier classes:
- (none)                — standard
- `gallery__item--tall` — taller, single column
- `gallery__item--wide` — spans two columns
