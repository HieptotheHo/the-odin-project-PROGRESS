
PRACTICING AT: COOL PHẾT
https://flukeout.github.io/

# Child and sibling combinators
- \> - the child combinator
- \+ - the adjacent sibling combinator
- \~ - the general sibling combinator

main 
    div class child group1
        div class grandchild group1
    div
    div class child group2
        div class grandchild group2
    div
    div class child group3
        div class grandchild group3
    div
main

+ main div {select all divs inside main}
+ main > div {select only child div of main}
+ main > div > div {select only grand child div of main}

.group1 + div {chon div child group2}
.group1 + div + div {chon div child group3}

.group1 ~ div {group1's siblings}

## Pseudo-selectors
### 1. Dynamic and user action pseudo-classes
- :focus
- :hover
- :active
- :link thay màu cho cái link
- :visited sau khi bấm vào link
### 2. Structural pseudo-classes
- :root
- :first-child
- :last-child
- :empty - element having no child
- :only-child element does not have any siblings
- :nth-child(even/5/3n)

### 3. Pseudo elements
- ::marker - styling li bullets
- ::first-letter 
- ::first-line
- ::selection - change highlights when user selects text
- ::before - add element before ...
- ::after - add element after ...

### 4. Attribute selectors
- [attribute]
 - selector[attribute]
- [attribute="value"]

