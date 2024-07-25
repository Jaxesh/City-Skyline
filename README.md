# City-Skyline
HTML Structure
<div class="background-buildings sky">: Contains the background buildings and the sky. This section has several buildings represented by divs with classes like bb1, bb2, etc.
<div class="foreground-buildings">: Contains the foreground buildings, also represented by divs with classes like fb1, fb2, etc.
CSS Styling
Variables: Defined under :root, these variables set the color scheme for the buildings and windows.
Global Styles: Applied to all elements using the * selector, ensuring consistent box-sizing and other properties.
Layout Styles: body, .background-buildings, and .foreground-buildings styles manage the overall layout, ensuring full-screen height and proper alignment.
Building Styles: Each building class (bb1, bb2, etc.) has its own style rules to define dimensions, colors, and gradients.
Responsive Design
An additional media query adjusts the color scheme for screens narrower than 1000px, switching to a monochromatic palette for better readability and aesthetics.

Notes:
The building-wrap and window-wrap classes are utility classes used to align and position building and window elements.
The .sky class sets the gradient background for the sky, giving a sunset or night effect depending on the screen size.
