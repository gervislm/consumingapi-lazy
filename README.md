# consumingapi-lazy
Fox Images API Consumption JavaScript App with Lazy Loading

## Overview

This is a simple JavaScript web application that consumes a Fox Images API to display random fox images. It incorporates lazy loading to enhance performance by only loading images as they become visible in the viewport.

## Features

- Fetches random fox images from the Fox Images API.
- Implements lazy loading to improve page load times.
- Provides a user-friendly interface to view and interact with the images.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone this repository:
   
   git clone https://github.com/gervislm/consumingapi-lazy.git
   
   
3. Navigate to the project directory:
   
   cd consumingapi-lazy

4. Install dependencies:
   
   npm install
   

## Usage

1. Start the application:
   
   npm start
   
   This will run the app on `http://localhost:3000`.

2. Open a web browser and go to `http://localhost:3000` to view the app.

## Implementation Details

- The application is built using JavaScript, HTML, and CSS.
- It uses the API to communicate with the Fox Images API.
- Lazy loading is implemented using the Intersection Observer API.
- The UI is designed with simplicity in mind, featuring a button to load new images.

## Folder Structure

- `src`: Contains JavaScript source code.
   - `index`: Main application component.
   - `lazy`: Reusable functions
     
- `styles`: Contains static files (CSS).
- `index.html`: Contains main HTML

## Contributing

Feel free to open an issue or submit a pull request for any improvements or new features you'd like to see.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [Fox Images API](https://randomfox.ca/floof/): Thank you for providing the adorable fox images!
