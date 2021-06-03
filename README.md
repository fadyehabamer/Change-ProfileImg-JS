# Change Profile Image 
> Like FaceBook 😉👌
using
- HTML
- CSS
 - Gradients
- JS
 - Built-in JS functions

```javascript
file.addEventListener("change", function() {
    const choosedfile = this.files[0];

    if (choosedfile) {
        const reader = new FileReader();

        reader.addEventListener("load", () => {
            img.setAttribute("src", reader.result)
        });
        reader.readAsDataURL(choosedfile)
    }
});
```
 
