# Hover Effect Button
This repository contains a simple HTML and CSS code snippet that creates an interactive hover effect button. When you hover over the button, it displays a captivating animation. Below, the working and explanation of the code are detailed.

## Demo
You can see a live demo of the hover effect button by opening the index.html file in your web browser or visiting : 

**https://hover-effect-buttons.vercel.app/**

## Features
**Interactive Hover Effect**: The button exhibits a vibrant gradient animation and blurring effect on hover, providing an engaging user experience.

**Versatility**: The code is written in a way that allows easy customization. You can adjust button size, colors, and animation speed to fit your design requirements.

## How it Works
### HTML Structure
The HTML file (index.html) contains two button elements wrapped inside outer div elements. Each button has two span elements that create the blur effect on hover.

<div class="outer button">
    <button>Click Me</button>
    <span></span>
    <span></span>
</div>
<div class="outer circle">
    <button>Click Me</button>
    <span></span>
    <span></span>
</div>

### CSS Styles
The styles are defined in the style.css file. Key aspects of the styles include:

#### General Styles: 
Applies a CSS reset by setting margin, padding, and box-sizing to ensure consistent styling across different browsers.
#### Body Styles:
**body**: Sets the body to be a grid container, horizontally and vertically centered with a black background.
#### Centering Styles:
**.center**: Uses flexbox to horizontally and vertically center its children elements.
#### Button Container Styles:
**.outer**: Defines a common style for both button containers, setting position to relative, adding margin, and setting a black background.
#### Button Styles:
**.button and .circle**: Styles for button dimensions and border-radius to create a circular shape for the .circle class.
#### Button and Span Positioning:
**outer button and outer span**: Positions the button and span elements at the center of their parent (.outer) using absolute positioning and transform property.
#### Button Text Styles:
**outer button**: Styles the button text with a black background, light gray text color, no outline, and a pointer cursor.
#### Blur Effect on Hover:
**.outer:hover span:nth-child(1) and .outer:hover span:nth-child(2)**: Applies a blur effect to the first and second span child elements of .outer when hovered over, creating a smooth transition effect.
#### Gradient and Animation on Hover:
**.outer:hover**: On hover, applies a linear gradient background transitioning from cyan to yellow to a pinkish shade. Also applies the circling animation for a rotating hue effect.
#### Hue Rotation Animation:
**@keyframes circling**: Defines the circling animation, which smoothly rotates the hue of the button from 0 to 360 degrees, creating a looping color animation.


## Getting Started
To run the code locally, follow these steps:

**Clone the Repository** :

git clone repository-url

Open index.html in a Web Browser:

Open the index.html file in your preferred web browser to see the hover effect button in action.

Feel free to modify the code to experiment with different colors, sizes, and animation speeds to suit your project requirements.

Happy Coding! 🚀
