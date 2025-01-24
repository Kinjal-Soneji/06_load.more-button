# Load More Products Web App

## Description
A simple web application that fetches and displays product information from the DummyJSON API with a "Load More" functionality. Users can progressively load product details in a paginated manner.

## Features
- Fetch products from DummyJSON API
- Display product details (title, thumbnail, price, description)
- Responsive grid layout
- Load More button to fetch additional products
- Automatic disable of Load More button when 100 products are loaded

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API

## Installation
1. Clone the repository
2. Open `index.html` in a web browser
3. No additional setup required

## API Reference
- Uses DummyJSON Products API
- Endpoint: `https://dummyjson.com/products`
- Fetches 10 products per request
- Supports pagination via `limit` and `skip` parameters

## Project Structure
- `index.html`: Main HTML structure
- `main.js`: JavaScript for API interaction and dynamic content rendering
- `style.css`: Styling for the application

## How It Works
1. Initial page load fetches first 10 products
2. "Load More" button triggers subsequent API calls
3. Products are dynamically added to the page
4. Button disables after loading 100 products

## Customization
Modify `main.js` to:
- Change number of products per load
- Adjust API endpoint
- Implement custom error handling
