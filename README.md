# Instagram Reel Downloader

This project is a simple and responsive web application that allows users to download Instagram reels by providing the URL. The interface is minimalistic, uses the **Poppins** font, and is styled for clarity and usability.

<style>
    body {
        font-family: 'Poppins', sans-serif;
    }
</style>

## Features
- **Responsive Design:** Ensures compatibility across various devices and screen sizes.
- **Poppins Font Integration:** Provides a modern and clean typography style.
- **Error Handling:** Displays user-friendly messages in case of an invalid URL or download issues.
- **Loading Spinner:** Indicates progress during the download request.

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/instagram-reel-downloader.git
   cd instagram-reel-downloader
   ```

2. **Open the `index.html` file in a browser:**
   Simply double-click the file or use a live server (e.g., VSCode Live Server) to launch the application.

## File Structure
```
.
├── index.html       # Main HTML file with the application interface.
├── style.css        # (Optional) If separating styles into a CSS file.
├── script.js        # (Optional) If separating JavaScript into a JS file.
├── README.md        # Documentation for the project.
```

## Customization

### Change Fonts
The project uses the **Poppins** font, loaded via Google Fonts:

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
```

To use a different font, update this `<link>` tag in the `index.html` file and replace the font-family in the CSS:

```css
body {
    font-family: 'YourPreferredFont', sans-serif;
}
```

## Usage

1. Enter the URL of the Instagram reel into the text input field.
2. Click the **Download** button.
3. A download link will appear if the request is successful. Click the link to download the video.

## Technologies Used
- **HTML5**
- **CSS3** (with Poppins font for styling)
- **JavaScript** (for fetching and displaying the download link)

## License
This project is open-source and available under the [MIT License](LICENSE).
