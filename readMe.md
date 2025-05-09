# Update CSS with JS

## How it works 

This web aplication works in a way when the variables of the input element changes, it affects the image element

### Walkthrough

- First, You'd have to set a root element of the CSS to be the defaulted values in the input element

- Then you apply this root to your img element by var() method, calling your root values

- You go to your javascript and call all input element using the querySelectorAll which create a nodeList

- There's a difference between a nodelist and an array in such a way that a nodelist doesn't have access to some array properties.

- we use a forEach method on the inputs to add an Eventlistener to each input to detect a change in the value of each inputs

- i discovered there's a problem because we want it to change on the fly while we are changing the value in realtime;

- we add another eventListener to each input which is called a mousemove;

- i think theres a better way to do it but i'd do my findings

- i created a suffix variable which will be used for when i input the value into the equation

- We'd call the root element by using the document.documentElement and change the property using the style.setProperty;

- it works now;


#### What i Learnt

I refreshed my brain about the using root values i had forgotten all about it, ive gotten so used to tailwind, and i also learnt the change addEventListener and the mousemove addEventlistener and i can also apply that to the portfolio im building for more animations o ti ye ee!!!. 


i also learned about the input attributes of color and range because this is my first seeing this bad boys.

i also refreshed my use of data- attributes because i treated this in the first phase of this study

i also learnt about applying css with js. ive seen someone use it once and its nice to know the trick behind it. id do well to use it in the future and be able to apply it if such arises