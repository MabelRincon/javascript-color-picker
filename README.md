# Color Picker Project

This is a simple color picker that allows you to choose any color and display the selected color's value in different formats (RGB, HSL, and Hex). Additionally, the background color changes to the selected color, and the font color adjusts for better readability based on the luminance of the selected color.

## Learning Objectives:

- Learn how to implement a color picker with dynamic color adjustments.
- Understand how to calculate luminance to ensure text readability based on background color.
- Explore responsive design techniques using relative units (`rem`) to ensure the interface adapts to different screen sizes.
- Gain experience in making the UI stylish and functional with modern CSS techniques.

## Mockup Reference:

The design and functionality of this project were inspired by a simple, intuitive color picker mockup. The mockup is a user-friendly interface that allows you to pick colors and view their RGB, HSL, and Hex values, with the added feature of adjusting font color for better readability.
<figure>
<img src="img/mockup-color-picker.png" alt="mockup-color-picker" style="width: 33%"/>
<figcaption>Mockup provided</figcaption>
</figure>

## Final Result:

- Please take into consideration that the displayed result may vary depending on the browser you use to open the link.
- You can get different functionalities if you open this Web App using Firefox rather than Google Chrome. See the difference in the images below:

### Google Chrome

<figure>
<img src="img/chrome.png" alt="Google-Chrome" style=width: 33%>
<figcaption>Chrome's color tools offer a different approach. Although you can't directly pick colors from your screen in his Linux version, you can effortlessly convert between RGB, HSL, and Hex color formats.</figcaption>
</figure>

### Mozilla Firefox

<div style="display: flex; justify-content: space-between;">
 <figure>
  <img src="img/firefox-main.png" alt="Mozilla Firefox">
  <figcaption>Main menu view in Mozilla Firefox.</figcaption>
</figure>

<figure>
  <img src="img/firefox-custom.png" alt="Mozilla Firefox">
  <figcaption>Want to grab a color from anywhere on your screen? Click the + button below Custom, pick the color picker, and add it to your palette! But you can't change color formats.</figcaption>
</figure>
</div>

The final implementation is live and accessible via GitHub Pages:
[Access Color Picker](https://mabelrincon.github.io/javascript-color-picker/)

### Features:

- **Color Initialization:** The color picker initializes with a default color of `#000000` (black) or `rgb(0, 0, 0)`.
- **Multiple Color Formats (available only in Google Chrome):** The color is set by default in **RGB** format, but you can easily switch between RGB, HSL, and Hex formats using the color selector.
- **Grab a color (available only in Firefox):** Any color on the screen (in or out of the browser) can be easily added to the palette by using the color picker option.
- **Hex Code Display:** Once a color is selected, the text `Selected Color: #hexcode` is displayed in the center of the color display area.
- **Font Color Adjustment:** The font color will change to white when the background color becomes dark enough, ensuring that the text remains readable. This is done by calculating the luminance of the selected color. For further details, refer to the script.js file. The values within the function are based on the 'magic number' principle in computer programming. [Magic number documentation](https://en.wikipedia.org/wiki/Magic_number_(programming))
- **Responsive Design:** The layout uses relative units (`rem`) to ensure that it adjusts to various screen sizes.
- **Stylish Design:** The color display and color input have subtle shadow effects to give the interface a sleek, modern look.

### Feedback and Contributions:

Feedback is welcome! Feel free to open issues or submit pull requests to suggest improvements or report any bugs.

------

**Author**: Mabel Rincon