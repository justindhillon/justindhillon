# React Best Practices

## NAMING CONVENTIONS

Component’s names should be written using pascal case:
```
Header.js
HeroBanner.js
CookieBanner.js
BlogListing.js
```
Non-components should be written using camel case:
```
myUtilityFile.js
cookieHelper.js
fetchApi.js
```
Unit test files should use the same name as its corresponding file:
```
CookieBanner.js
CookieBanner.test.js

fetchData.js
fetchData.test.js
```
Attribute name should be camel case:
```
className
onClick
```
Inline styles should be camel case:
```
<div style={{font-size:'1rem'}}></div>
```
Variable names should be camel case. Variable names can contain number and special characters:
```
const variable = 'test';
let variableBoolean = true;
```
CSS files should be named the same as the component:
```
CookieBanner.css
Header.css
```
If a component requires multiple files (css, test) locate all files within component a folder <br><br>
Use .jsx or .tsx extension a for React components

## Credits
[JONDJONES.COM](https://www.jondjones.com/)
