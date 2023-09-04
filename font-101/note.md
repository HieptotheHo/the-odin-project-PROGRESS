## font stacking: 
body {
  font-family: system-ui, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
}

## Dùng font có sẵn trên API: có 2 cách
link và import
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">

@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

## Dùng downloaded font
@font-face {
  font-family: my-cool-font;
  src: url(../fonts/the-font-file.woff);
}

h1 {
  font-family: my-cool-font, sans-serif;
}


## Text styles
1. font-style: itatlic;
  hoặc dùng <em>
2. letter-spacing
3. line-height
4. text-transform uppercase
https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform
5. text-shadow
https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow
6. ellipsis