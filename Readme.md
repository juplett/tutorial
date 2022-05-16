# How to use ```<dialog>```

Whithin this tutorial we will be looking at how properly use the ```<dialog>``` tag <br>
As well as when, and where you should implement it into you code. <br>
In this tutorial we will be taking a look at how to use it with HTML, CSS, and javascrip <br>

## What is ```<dialog>``` 

A dialog tag is a relativly simple tag that can be used in a various different ways. <br>
Such as a dismissible ```alert```, ```inspector```, or ```subwindow```. <br>
But what is it? The ```<dialog>``` tag is a tag that provides you with a simple and ready to use information window <br>

## How to use ```<dialog>```

When using a ```<dialog>``` tag you want to know before had what your going to be using it for <br>
you dont want to put it into your code then realise you could have used sometyhing else and have had <br>
your code writin in a more simplistice and readable manner. When you do use it know that it is only <br>
really going to be used to hold ```dialogs```, or ```error``` messages; otherwise you are going to want to use a <br>
```<div>``` tag or something like that so that you are able to modify and use it in more than a couple different ways. <br>

Using the ```<dialog>``` tag is like using any other tag. You open the tag add in what you want inside of it the close the tag <br>
When using the ```<dialog>``` tag however you do have to clarify within the tag if it is open or not; That will let the computer know <br>
wither or not the tag is to be visable or not. And althought you can change wether the tag is vsiable or not in JS, you still have to <br>
set the defalt inside of the tag. Other than that they way to style and use it in js is pretty much the same as any other container tag <br>
as you can see in the img below.

```javascript
(function() {    
    var dialog = document.getElementById('myFirstDialog');    
    document.getElementById('show').onclick = function() {    
        dialog.show();    
    };    
    document.getElementById('hide').onclick = function() {    
        dialog.close();    
    };    
})();  
```

## References

* [Mozilla.org](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog)
* [Javapoint.com](https://www.javatpoint.com/html-dialog-tag#:~:text=HTML%20tag%20is%20used,new%20tag%20introduced%20in%20HTML5.)
* [W3schools.com](https://www.w3schools.com/tags/tag_dialog.asp)
