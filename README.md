# Advanced_forms
Advanced web forms 

Key observations:

* Every input element has some border style set to inset (border-top is always black) . Reset that using border-style="solid" or with border-color
* Wrap Every input element with a wrapper that makes your life easy while styling
* Make sure you always add label to the input element and attach for with input id
* Define width for label element for better alignment 
* Radio-Buttons - Using fieldset with legened while using radio buttons since they works in groups and name attribute should be same for all buttons.
* Accept-characterset- [UTF_8,ISO]
* Always select an encoding type for your form that can handle all the character that you inteneded user to write -(theta ?)
* Input type = Hidden
* #1. Hidden input fields may be handy if, for example, you have several forms on different pages on your website and you want to identify which page the visitor was on when they filled out the form.

#2. You may want to include a timestamp of when the user submitted the form.

#3. Another use of hidden inputs is to know what entry a user is editing so that you can update the correct row in the database when the user submits the form. The user doesn't need to edit (or even know) the ID of the entry, so a hidden field works well here.
