# Dev Blog Application

#### A single-page blog application for creating, reading, updating, and deleting blog posts with a clean, responsive interface.

#### By **[James Kamau]**

## Description

This application is a fully functional blog system built with vanilla JavaScript that demonstrates modern frontend development practices. It features CRUD operations (Create, Read, Update, Delete) for blog posts, with a clean user interface and responsive design.

## Screenshot

![Dev Blog Interface](./screenshot.png) <!-- Add your screenshot path here -->

## Features

- View all blog posts in a clean list layout
- Create new blog posts with title, author, content, and optional image
- Read full post details in a dedicated view
- Edit existing posts
- Delete posts with confirmation
- Like posts (with like counter)
- Responsive design that works on all devices
- Loading states and error handling
- Empty state management

## How to Use

### Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for API access)

### Using the Live Application

1. Visit [the deployed site](#) <!-- Add your deployment URL here -->
2. Browse existing posts in the list
3. Click any post to view details
4. Use the form to create new posts
5. Edit or delete posts using the action buttons

### Local Development

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/jameskamau-5773/dev-blog.git
   cd dev-blog
2. Open index.html in your browser (connects to live API by default)

3. For local API development:
    npm install -g json-server
    json-server --watch db.json --port 3001

  Then update the API_BASE_URL in index.js to http://localhost:3001

## API Reference

### Base URL
  https://challange-json-server-1.onrender.com

### Endpoints

Method	     Endpoint	               Description
GET	         /posts	             Retrieve all blog posts
GET	         /posts/:id	         Retrieve single blog post
POST	       /posts	             Create new blog post
PATCH	       /posts/:id	         Update existing blog post
DELETE	     /posts/:id	         Delete blog post

### Technologies Used

Frontend: HTML5, CSS3, Vanilla JavaScript (ES6+)

Backend: JSON Server hosted on Render

Styling: Custom CSS with responsive design principles

Architecture: Modular JavaScript with clear separation of concerns

### Code Structure
dev-blog/
├── index.html          # Main HTML file
├── styling.css         # All CSS styles
├── index.js            # Main JavaScript application
└── assets/             # Optional assets folder
    └── images/         # For any local images

### Key JavaScript Features

Async/await for API calls

DOM manipulation without jQuery

Event delegation

Form handling and validation

Error handling and user feedback

State management through UI updates

### Support and Contact Details

For questions or support:
Email: [jamesnk5773@gmail.com]

GitHub: [@jameskamau-5773]

## License

  MIT License
  Copyright © 2025 [james kamau]

  Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
  
 The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
