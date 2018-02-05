# CSS Layout Basics

### Positioning
---

#### Inline Display
* There are block level elements and inline level elements
    * Block Elements:
        * h tags
        * p tags
        * divs
    * Inline Elements:
        * imgs
        * a tags
        * spans
* Inline elements naturally flow next to eachother
* Inline elements do not take in vertical margin and padding values, on horizontal
* Inline-block lets you style an inline element as you would a block element while keeping it in the same line as the elements next to it

#### Remove Spaces Between Inline or Inline Block Elements
* The spaces between the elements results from the literal spaces in the markup
* You can put the opening and closing <li> tags on the same line but this is not recommended
* Add a negative margin, this will remove the default white space
    * Note that element font size will affect how much negative margin you will need to apply

#### Floats
* Similar to inline, but floated elements are taken out of the normal document flow
    * Other content will flow around them
![Float Image](img/floats.png)
* Be default, browsers display elements in the order they appear in the HTML source code. This is called Normal Document Flow
    * These elements are either block or inline
    * They appear stacked or inline with eachother
* When an element has a flow property it is taken out of this normal flow and shifted to the left or right side of it's container
* Any content next to the float will flow, or wrap, around it's left or right side
* 