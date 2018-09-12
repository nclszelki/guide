---
title: Match Single Character with Multiple Possibilities
---
## Match Single Character with Multiple Possibilities


<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
Hint:
We need to match more than one result and we need to match case insenstive result.




#Solution:
```
    let vowelRegex = /[aeiou]/ig; 
    let result = quoteSample.match(vowelRegex); 
```
