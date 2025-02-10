# scene-generation
This web application allows users to upload an image, apply tilt and rotation transformations, and generate multiple variations of the image. The main image remains interactive, supporting zooming using the mouse scroll or pinch gestures. The application also provides an option to export the transformed images.

Image Tilt & Rotate Web Application

Overview

This web application allows users to upload an image and apply transformations such as rotation and tilt. The main image remains interactive, allowing zooming with the mouse. Additionally, four transformed versions of the image (rotated, tilted, combined, and flipped) are displayed alongside the main image with export functionality.

Features

Image Upload: Users can upload an image file.

Rotation & Tilt: Sliders allow users to rotate and tilt the image.

Interactive Main Image: Supports zoom in/out via the mouse wheel.

Side Output Images: Displays four variations of the transformed image.

Export Option: Each output image has an export button.

Responsive UI: Clean, structured layout with a user-friendly interface.

Technologies Used

HTML: For structuring the webpage.

CSS: For styling and responsive design.

JavaScript: For implementing interactivity and transformations.

Canvas API: Used for rendering images and transformations.

Code Structure

HTML Tags Used:

<input type="file"> - For uploading images.

<input type="range"> - For rotation and tilt controls.

<canvas> - For rendering the interactive main image.

<div> - For layout structuring.

<button> - For user interaction (reset and export actions).

CSS Styling:

body: Center-aligned, light background.

#controls: Sidebar with sliders and buttons.

.image-container: Holds the main image and output images.

canvas: Displays the main interactive image.

.image-box: Contains output images with titles and buttons.

JavaScript Functionality:

Image Upload Handling

Uses FileReader to load images.

Draws the image on <canvas>.

Rotation & Tilt Transformation

Uses transform CSS property (rotate, skewY).

Updates preview images dynamically.

Interactive Zoom for Main Image

wheel event listener adjusts the scale.

Generate Output Images

Creates four variations with different transformations.

Export Images

Converts <canvas> output to downloadable PNG files.

How to Use

Open the web page in a browser.

Upload an image using the file input.

Adjust rotation and tilt using sliders.

View the main image and output variations.

Click "Export Image" to download any output.

Future Enhancements

Add camera controls for dynamic image positioning.

Implement additional transformation effects.

Improve UI with animations.
