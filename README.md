# Client-Side Captcha Verification Demo

This project provides a simple, client-side web application for demonstrating captcha verification. It's built with responsive design principles using Tailwind CSS and allows users to input text to verify against a displayed captcha image.

## Features

-   **Responsive Design**: Adapts to various screen sizes, ensuring a good user experience on both desktop and mobile devices.
-   **Tailwind CSS**: Utilizes the utility-first CSS framework for rapid and consistent styling.
-   **Dynamic Image Loading**: The captcha image can be loaded either from a local `sample.png` file (default) or from an external URL provided via a query parameter (`?url=https://example.com/image.png`).
-   **Client-Side Verification**: Users can enter their interpretation of the captcha text, and the application provides immediate feedback on correctness.

## How to Use

1.  **Open `index.html`**: Simply open the `index.html` file in your web browser.
    *   By default, it will display the `sample.png` captcha image.
2.  **Load Custom Captcha (Optional)**: To load a captcha image from a specific URL, append a `?url=` query parameter to your browser's address bar.
    *   Example: `file:///path/to/your/project/index.html?url=https://picsum.photos/200/50?random=1` (replace with an actual image URL if needed, though for this specific demo, the expected text is hardcoded to "ADQRB").
    *   For the provided `sample.png` and the implicit "ADQRB" solution, even if you load a different image, you would still enter "ADQRB" to verify successfully in this demo.
3.  **Enter Captcha**: Type the text you see in the captcha image into the input field.
4.  **Verify**: Click the "Verify Captcha" button or press Enter to check your input.
5.  **Reload**: Click "Reload Captcha" to re-evaluate the URL parameter and reload the image.

## Technologies Used

-   HTML5
-   Tailwind CSS (via CDN)
-   JavaScript

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.