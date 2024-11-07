# Image Search App

A simple web application that allows users to search and browse images based on keywords, using the Unsplash API.

## Features
- **Search Images**: Enter keywords to search for relevant images.
- **Show More Results**: Load additional images with the "Show More" button.
- **Responsive Design**: Optimized for various screen sizes.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/rasrescodes/image-search-app.git
   ```
2. **Navigate into the project folder**:
   ```bash
   cd image-search-app
   ```
3. **Open `index.html` in your browser**:
   You can run the app by simply opening the `index.html` file in your preferred web browser.

## Usage

1. Enter a keyword (e.g., "nature") in the search box and click **Search**.
2. View the results and click **Show More** to load additional images if available.

## API Key Setup

This app requires an API key from [Unsplash](https://unsplash.com/developers). Replace the `accessKey` variable in `index.js` with your key:

```javascript
const accessKey = "YOUR_ACCESS_KEY";
```

## Project Structure
- `index.html`: The main HTML file that structures the app.
- `style.css`: The CSS file for styling the app’s layout and responsiveness.
- `index.js`: The JavaScript file handling the search functionality and Unsplash API integration.

## License
This project is open source and available under the MIT License.

## Acknowledgments
Thanks to the [Unsplash API](https://unsplash.com/developers) for providing free access to high-quality images.
