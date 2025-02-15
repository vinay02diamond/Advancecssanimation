# Animation Project

This project demonstrates a simple CSS animation using HTML and CSS. The animation changes the background color of a box and moves it around the screen.

## Files

- `index.html`: The HTML file containing the structure of the web page.
- `advancecssanimationdesign.css`: The CSS file containing the styles and animations for the web page.

## How to Run the Project

1. Clone the repository to your local machine.
2. Open the `index.html` file in your web browser.

## HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Animation</title>
    <link rel="stylesheet" href="advancecssanimationdesign.css">
</head>
<body>
    <div class="box">
        <p>Hello  there!</p>
    </div>
</body>
</html>

.box {
    height: 100px;
    width: 100px;
    background-color: red;
    position: relative;
    animation-name: demoAnimation2;
    animation-duration: 10s;
    animation-iteration-count: infinite;
}

@keyframes demoAnimation {
    from {
        background-color: red;
    }
    to {
        background-color: blue;
    }
}

@keyframes demoAnimation2 {
    0% {
        background-color: red;
        top: 0px;
        left: 0px;
    }
    25% {
        background-color: green;
        top: 0px;
        left: 300px;
    }
    50% {
        background-color: yellow;
        top: 300px;
        left: 300px;
    }
    75% {
        background-color: aqua;
        top: 300px;
        left: 0px;
    }
    100% {
        background-color: purple;
        top: 0px;
        left: 0px;
    }
}




