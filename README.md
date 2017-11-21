# imgr
lightweight image cropper

```html
<link rel="stylesheet" href="imgr.min.css">
<script src="imgr.min.js"></script>
```

```html
<input type="file" id="crop">
```

```html
<script>
var crop = new Imgr("#crop",{
  size : {
    width : 600,
    height : 600
  },
  ratio : 0.5,
  quality: 0.9,
  callback : function(result){
    document.body.appendChild(result);
  }
});
</script>
```
