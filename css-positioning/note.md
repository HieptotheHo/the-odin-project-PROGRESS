### Static: không dùng right, left, top, bottom
### Relative: hệt static, dùng right, left, top, bottom được
không nên dùng relative!!!

### Absolute: out of the flow of the document, relative to the NON-STATIC PARENTS

### FIXED: relative to the html tag: dùng để cho navbar
"Move with the page as you scroll"


### sticky: become fixed at a certain declared location 
------------------
### CSS Custom Property
- --color: white;
- background-color(white, fallback);
- scope: nếu declare ở 1 thẻ nào đó thì nó chỉ apply cho nó và các con của nó
- :root thì sẽ globally applied

- @media(prefers-color-scheme: dark) - sẽ tìm kiếm preference của user trên browser mà set theo. Nói chung là tăng UX 
