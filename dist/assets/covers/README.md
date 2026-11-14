# Book cover slots

Place supplied cover images in this folder, then set each story's `cover` value in
`dist/index.html` to its relative path, for example:

```js
cover: "./assets/covers/pride-and-prejudice.jpg"
```

Portrait artwork around a 2:3 aspect ratio is recommended. Images are cropped with
`object-fit: cover`, so different portrait dimensions are supported.
