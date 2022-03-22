
<!DOCTYPE html>

# meta
* informtion about the HTML doc
* machine parsable
* global attributes
---
### charset
```
<meta charset="UTF-8">
```
* encoding of the HTML document

### ASCII (American Standard Code for Information Interchange), ISO-8859-1, Symbol
* 7 Bit rep
* 128 Characters

    ```
    0 - 48
    9 - 57
    A - 65
    a - 97
    ```
* ISO-8859-1:
    * The International Standards Organization
    * HTML4
    * Diff from Windows-1253 : some symbols like euro, cross are not used in ISO

### Symbol: 

``` 
&euro 
```
---
```
<meta name="author" content="bharath s">
```
---
### viewport
```
<meta name="viewport" content="width=device-width, inital-scale=1.0"> 
```
* viewport : users visible area of a web page
* helps browser how to control the page's dimension and scaling
* intial-scale: 1.0 -> sets the inital zoom
---
### link
```    
<link rel="stylesheet" href="home.css"/>
```
* link: defines relationship btw current doc & external resourcce
* rel: type of relation
* href: destination of the link
---