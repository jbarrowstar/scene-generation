# scene-generation
This web application allows users to upload an image, apply tilt and rotation transformations, and generate multiple variations of the image. The main image remains interactive, supporting zooming using the mouse scroll or pinch gestures. The application also provides an option to export the transformed images.
# Image Tilt & Rotate Web Application

## Overview
This project is a web-based application that allows users to upload an image, apply tilt and rotation transformations, and generate variations with labeled angles. The main image is interactive, supporting zooming and panning, while four additional transformed images are displayed as output with export options.

## Features
- Upload an image and apply tilt/rotate transformations
- Interactive main image with mouse zoom and pan
- Four transformed images with labeled rotation/tilt angles
- Individual export buttons for each output image
- User-friendly UI with clean design and responsive layout

## Technologies Used
- **HTML**: Structure of the webpage
- **CSS**: Styling and layout
- **JavaScript**: Handling transformations, interactivity, and image processing
- **Three.js**: Rendering interactive 3D transformations

## File Structure
```
project-folder/
│── index.html    # Main application file
│── styles.css    # Custom styles
│── script.js     # JavaScript for interactivity
│── README.md     # Project documentation
```

## Usage Instructions
1. Open `index.html` in a browser.
2. Click on `Choose File` to upload an image.
3. Use the `Rotate` and `Tilt` sliders to adjust the image.
4. View the transformed images below the main image.
5. Click `Export Image` under any image to download it.

## HTML Structure
The webpage consists of:
- **File Input**: `<input type="file">` for image upload
- **Sliders**: `<input type="range">` for rotation and tilt adjustments
- **Canvas**: `<canvas>` for rendering the main image
- **Div Containers**: `<div>` for output images
- **Buttons**: `<button>` for exporting images

## JavaScript Functionality
- **Image Upload**: Reads the uploaded file and renders it on the canvas.
- **Interactive Main Image**: Supports zooming and panning.
- **Transformation Logic**: Applies tilt and rotation using CSS `transform`.
- **Export Function**: Captures the transformed image and downloads it.

## CSS Styling
- Uses **flexbox** for layout organization.
- Buttons have **hover effects** for better UI experience.
- Outputs are **responsive** to different screen sizes.

## Future Enhancements
- Add more transformation effects.
- Implement real-time preview before applying changes.
- Enhance export functionality with adjustable resolution options.

## Author
Developed by JB Arrowstar 

