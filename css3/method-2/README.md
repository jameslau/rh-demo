# RH-DEMO: CSS EXERCISE #3 / METHOD-2

### Project solution
Floats can cause issues when not set properly. An alternative solution is to play with positioning (relative, absolute) of HTML elements.

1. First, set the parent `body` div to `postion: relative;`. 

2. Wrap the sections `article > title` and `aside` with a `section` div and give it a class of `container`. Give the container property values of: `position: relative; display: block; width: 100%; height: auto;`

3. Remove `floats` from `section` and `aside` and reassign them with `position: absolute;`. 

4. Give `section` property value of `left: 0px;` and `aside` section a property value of `right: 0px;`.

5. Override `article` section property value with: `padding-left: 0px; padding-right: 0px; border: 16px solid lightgreen;`. This will plug the title boxes back into place with a border as designed.