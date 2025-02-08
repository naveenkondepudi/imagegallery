A responsive and interactive image gallery that displays images in a grid layout. The gallery supports a lightbox feature that allows users to view larger versions of images, navigate through them, and close the lightbox by clicking on the overlay or close button.

Features
Grid Layout: Displays images in a clean, responsive grid format.
Hover Effects: Images slightly zoom in when hovered for better interactivity.
Lightbox: Allows users to view images in a larger format, with navigation options to go through the images.
Navigation: Users can navigate between images using the previous and next buttons in the lightbox.
Close Lightbox: Close the lightbox by clicking the close button or the background overlay.
Technologies Used
HTML: For structuring the image gallery and the lightbox.
CSS: For styling the gallery layout, hover effects, and the lightbox.
JavaScript: Implements the lightbox functionality, including opening, closing, and navigating images.
Installation
To run this project locally:

Clone the repository (or download the files):

bash
Copy
Edit
git clone <repository-url>
Open the index.html file in any web browser to see the gallery in action.

Alternatively, you can download the HTML, CSS, and JavaScript files and open the index.html directly in your browser.

File Structure
bash
Copy
Edit
/Image-Gallery
├── index.html        # Main HTML file with the gallery layout and lightbox functionality
├── styles.css        # The CSS file with styling for the gallery and lightbox
└── README.md         # The README file providing project details
How to Use
Viewing Images: The gallery displays a collection of images. Click on any image to open it in the lightbox.
Navigating in Lightbox: In the lightbox, use the left (←) and right (→) arrows to cycle through images.
Close Lightbox: Close the lightbox by clicking the "X" button or anywhere outside the image.
Code Explanation
The HTML provides the gallery structure, each image is wrapped in a <div> with the gallery class.
CSS styles the gallery layout with a grid display and provides hover effects for the images. The lightbox is hidden initially, and its display is triggered by JavaScript when an image is clicked.
JavaScript handles the logic for opening and closing the lightbox, changing the images when navigating with the previous/next buttons, and closing the lightbox when the overlay is clicked.
Demo
You can view a live demo of the gallery hosted on any platform (e.g., GitHub Pages or Netlify). Alternatively, you can host it yourself for testing purposes.

Notes
The gallery images are hardcoded, but you can easily extend it by adding more <img> elements within the .gallery container.
The project uses simple JavaScript and does not require any additional libraries or frameworks.
License
This project is open-source and available under the MIT License.

