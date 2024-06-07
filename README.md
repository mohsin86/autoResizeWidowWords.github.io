# autoResizeWidowWords
Detecting and auto resize if widow/single words exists on rendered text
Objective: The font should autosize to fit the widow on the line above if string has widow words.
Reduce font size to fit the string in the container if string has widow words.

Usage
-----
```ruby
 // Just call the functionin with element

// Use if only texNode, no child element
fitWidowWordsTextNode("#headline");
        
// Use if multiple child element exists
fitWidowWords(".text-container2");



 
```
