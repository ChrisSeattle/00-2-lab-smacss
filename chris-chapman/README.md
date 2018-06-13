##### How did you determine which rules should be placed in each new CSS file?

It seems to make sense that base.css should hold the style rules that seemed to be the same throughout the page, or at least the default unless there is a more specific rule for a more specific context. After that I looked at the rules that seemed to be targeting just the layout parts of the page and placed those in the layout.js file. The styling that was uniquely related to the input element or elements with the class of recipe, or elements inside of elements with that class, all seemed to make sense for the module.css file (though I could see arguements for doing those diffrently). 
---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

This was mostly just copy and paste from the original style.css . I don't think I had to change anything really. If I did it was minor enough that I don't really remember changing it. 