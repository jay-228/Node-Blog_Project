### **Objective**

Create a full-stack web application titled **"Blog Details"** using **React.js** for the frontend and **Node.js, Express, and MongoDB** for the backend. The application should allow users to perform **CRUD (Create, Read, Update, Delete)** operations on a collection of blog posts.

### **Requirements**

1. **Frontend (React.js)**:
    - Build a user interface that supports the following features:
        - **Create a New Blog Post**: A form for adding new posts.
        - **View All Blog Posts**: Display a list of all posts with details like title, author, content, and tags.
        - **Update a Blog Post**: A form to update an existing post.
        - **Delete a Blog Post**: A button to delete a post from the list.
    - The frontend should be responsive and styled using **CSS** or **Bootstrap**.
2. **Backend (Node.js, Express, MongoDB)**:
    - Set up an **Express API** to handle the CRUD operations:
        - **GET /posts**: Retrieve all blog posts from the MongoDB database.
        - **POST /posts**: Add a new post to the database.
        - **PUT /posts/**: Update an existing post by its ID.
        - **DELETE /posts/**: Remove a post by its ID.
    - Use **Mongoose** to define the blog post schema and interact with MongoDB.
3. **MongoDB**:
    - The **BlogPost** model should include the following fields:
        - Title (String)
        - Author (String)
        - Content (String)
        - Tags (Array of Strings)
        - Published Date (Date)
    - Store blog post details in a MongoDB database.
4. **Routing & Communication**:
    - Use **Axios** or **Fetch API** to handle communication between the React frontend and Express backend.
    - Ensure frontend handles server responses, including success/error messages.

### **Instructions**

1. **Backend Setup (Node.js, Express, MongoDB)**:
    - Initialize a Node.js project, install required dependencies (express, mongoose, cors, dotenv, etc.), and set up routes and controllers for CRUD operations.
    - Connect MongoDB using **Mongoose**.
2. **Frontend Setup (React.js)**:
    - Initialize a React app and install Axios or use Fetch API for HTTP requests.
    - Create components for:
        - **BlogList**: Displays all posts.
        - **BlogForm**: For adding and updating posts.
        - **BlogDetails**: Shows detailed information on a single post.
    - Set up routing using **React Router**.
