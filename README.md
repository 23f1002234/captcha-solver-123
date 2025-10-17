# Captcha Solver Frontend

This project provides a simple, responsive web interface for displaying captcha images and allowing users to input their solutions. It's built with modern web technologies, focusing on a clean user experience and ease of use.

## Features

*   **Responsive Design:** Optimized for various screen sizes, from mobile devices to desktops, using Tailwind CSS.
*   **Dynamic Image Loading:** Displays a default local image (`sample.png`) or loads a captcha image from a URL specified in the query parameters.
*   **User Input Field:** A dedicated input field for users to type their captcha solution.
*   **Client-Side Validation (Example):** Includes a basic client-side check for a specific captcha (`ADURS`) as an example. In a production environment, captcha validation would typically occur on the server-side.
*   **Simple & Clean UI:** Powered by Tailwind CSS for a modern and accessible design.

## How to Use

### Running Locally

1.  **Save the files:** Save `index.html`, `README.md`, `LICENSE`, and `sample.png` in the same directory.
2.  **Open `index.html`:** Simply open the `index.html` file in your web browser.

### Loading Custom Captcha Images

You can load a custom captcha image by appending a `url` query parameter to the `index.html` file.

**Example:**

`index.html?url=https://example.com/path/to/your/image.png`

If no `url` parameter is provided, the application will default to displaying `sample.png`.

### Solving the Captcha

1.  Observe the captcha image displayed.
2.  Type the text you see in the image into the input field.
3.  Click the "Submit" button or press `Enter`.
4.  A message will indicate whether your solution was correct or incorrect (for the `sample.png` image, the correct answer is "ADURS").

## Technologies Used

*   **HTML5:** For the page structure.
*   **Tailwind CSS:** For utility-first styling and responsive design.
*   **JavaScript (ES6+):** For dynamic content, URL parameter handling, and client-side logic.