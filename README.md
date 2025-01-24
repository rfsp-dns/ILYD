# ILYD-Library

ILYD-Library is a new library for people who want to use only JavaScript to create webpages, for now it's designed to be a library for an game I'm making.

ILYD-Library will have many components to create a responsive and dynamic HTML webpage, the main focus of this library is for 2D Games.

ILYD-Library for now is just a project in mind, but I already have some code that will work like below.


# ILYD Components

- Menu
- HeavyText
- Button


# ILYD Example

Here's a simple approach of using ILYD-Library : 

## index.html
``` 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <script src="./library/Components.js"></script>
    <script src="./library/Options.js"></script>
    <script src="./library/Button.js"></script>
    <script src="./library/Menu.js"></script>
    <script src="index.js"></script>
</body>
</html>
```

## index.js
```
const parentElement = document.body; //Getting the body from the html
setBackground(parentElement, 'https://i.pinimg.com/originals/59/69/84/59698460a33a71e42ddf46e185e17737.gif') //Setting background of body to an gif

const menu = new Menu(parentElement) //Creating an element called menu

menu.setBackground("https://i.pinimg.com/originals/ca/e1/1d/cae11df222ff8639d02aa7b81d1d296a.gif"); //Setting element menu a background gif
new HeavyText(menu.getHeader(), 'Banana Frita'); //Creating a title in the Menu Header
const button = new Button(menu.getBody(), 11, 'Create a new Button here!'); //Creating a button on the Menu Body

```

# Support

My main focus on this project is to get people who don't know to program to create some games dating sim like and for this I will try to create a language HTML alike using the Component's names and much more.

Wish me luck
