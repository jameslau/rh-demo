# RH-DEMO: CSS EXERCISE #2 / Version #2

This is the second exercise out of three CSS exercises. You will need the following files and folders in order to view the project. Please pull down the code from the main RH-DEMO page for the complete project library.  

```
index.html
/css 
/font
overpass font (https://github.com/RedHatBrand/Overpass)   
```

### View project
- open index.html from the rh-demo/css2v2 in your browser   

<br>

UPDATE: Revised markup structure and utilized a flexbox method for the CSS. All other files and major folder structures stay the same.  

### Changelog
- [x] Use flexbox to center the panel horizontally and vertically in the browser window
- [x] Use flexbox on the panel header with flex properties to position the "openshift" text and navigation menu
- [x] Use flexbox to position the elements within the navigation menu
- [x] Use a `dl` to represent the case details, and use flexbox to position the title/value pairs
- [x] Remove the extra right border on the last navigation element in the header
- [x] Ensure the entire space in each navigation element is clickable (not just the text), and make sure the :hover state CSS is only applied to the clickable area of the element
- [x] Clean up the HTML and CSS - remove anything that is unnecessary, unused, and consolidate any duplicate CSS where it makes sense to do so by using a single selector or combining selectors
- [x] Ensure everything is responsive down to 320px

### Flexbox Guides
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox
- https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Controlling_Ratios_of_Flex_Items_Along_the_Main_Ax

### Findings
 > Within a single dl element, there should not be more than one dt element for each name.
(http://html5doctor.com/the-dl-element/)
- https://stackoverflow.com/questions/19026884/flexbox-center-horizontally-and-vertically
- https://www.sitepoint.com/community/t/flexbox-with-block-link/224913/3

