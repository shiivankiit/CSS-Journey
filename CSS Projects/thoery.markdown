
Units----
px=pixels which is less used because it does not change with respect to screen
%= total screen ka hisa adjust according to the screen. and it takes value with its parent
vw and vh screen se calue leta ha.

em dpnd karta ha us element ke font size par,aur ye agar parent ko deta hai to children par bhi apply hota ha.

means: consider kariye ek element hai jiske pass 16px font size hai to 1em ki value 16px hogi aur agar
font size change kiya to uske response mein em ki value bhi badhegi.

rem:- Root element 
1rem=16px.
max-width and max-height :-Puts restriction on the page..that nothing goes beyond that.

Display-properties:
Block element takes full width of the page.
While inline element takes the required width on the page.
inline-block___you can set margina and padding to it.

Position:
postion:absolut---element upar utha jayega.and travel anywhere in the page.
position:relative--creates a border for its child elem so that they can not go beyond that

Flexbox:
It is not applying on children ..applies it on parent.

Pseduo-element:--
Two properties -before and after.
p{before} and p{after}.
::first-line
::first-letter
::selection

pseudo-classes::-- hover,active,focus,nth-child()

CSS-colors:-
screen show mainly three color.

Grid:---
Display grid is a two dimnesional property.


# Responsive in CSS

## Understanding Units
-px
-%  //adjust accord to their parent
-vw,vh  // takes value from the full screen size.
-vmax,vmin  // jo viewport maximum ho uske according adjust kar lo.
-em,//takes value from parent and 1em,2em means double the value of child.
rem-root element
according to the screen size
1rem=16px

## Layout of website
-absolute vs flex.
 
## flexbox
-Display flex
-aligning items in x and y axis
-flex direction
-flex wrap //set elem to the next line instead of shrinking them

## CSS media Queries

parent:box
#box{
    height:500px;
    width:500px;
    bg-color:royal-blue;
}
@media (max-width:600px){
    #box{
        bg-color:crimson;
    }
}