## This will *not* have any css in it. Instead, it will have JSON.

Here's an example of some "css":
```json
// stuf.json (WITHOUT THE COMMENT)
{
  "classes" : {
    "black" : {
      "background-color" : "#000"
    }
  },
  "ids" : {
    "login" : {
      "text-align" : "center"
    }
  }
}
```
Which is roughly eqivalent to the following:
```css
/* stuf.css */
.black {
  background-color: black;
}
#login { 
  text-align: center;
}
```
