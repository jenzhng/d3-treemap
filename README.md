# D3 Treemap Example

Welcome to the D3 Treemap Example repository! This project demonstrates how to create a treemap visualization using D3.js. Treemaps are a space-filling visualization technique that displays hierarchical data as a set of nested rectangles.

## Features

- **Interactive Treemap**: Displays hierarchical data using a set of nested rectangles.
- **Dynamic Highlighting**: Hovering over a rectangle (quad) highlights it for better inspection.
- **Pastel Colors**: The treemap uses pastel colors for better visual appeal and differentiation.

## Live Demo

You can view the live demo of this project at: [D3 Treemap Demo](https://jenzhng.github.io/d3-treemap/)

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/jenzhng/d3-treemap.git
2. **Navigate to the Project Directory**

   ```bash
   cd d3-treemap
3. **Install Dependencies**
  This project uses npm for dependency management. Ensure you have Node.js and npm installed, then run:
   ```bash
   npm install
4. **Run the Project**
   Start a local development server to view the project:
   ```bash
   npm start
   The application will be available at **`http://localhost:3000`**.

## Usage

Open the Application: Navigate to **`http://localhost:3000`** in your web browser to view the treemap visualization.
Interact with the Treemap: Hover over different rectangles to see them highlighted and explore the hierarchical data representation.

## Data Format

This project uses hierarchical JSON data for the treemap. Ensure your data follows this structure:
   ```json
   {
     "name": "root",
     "children": [
       {
         "name": "A",
         "size": 100
       },
       {
         "name": "B",
         "size": 200
       }
     ]
   }

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or feedback, please contact jenzhng.

