# Playlist-library
Create a movie library web app with user authentication (Sign In/Sign Up). After logging in, users can search movies using the OMDB API and view details. Users can create, view, and manage movie lists (like YouTube playlists), with options for public or private visibility. The home page displays user-created lists.
# npm installation
1. Open the terminal and execute "npm install" to install all the dependencies.
   
2. Start the application by running "npm start".
   
3. Initialize the project by running "npm init".
   
5. Install the Express framework by running "npm install express".
   
6. Install EJS by running npm install ejs.
   To use EJS in your project, include the following lines in index.js:
   app.set('view engine', 'ejs');
   app.set('views', './views');
   
7. Install Mongoose: Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment, supporting both promises and callbacks. Install it by running "npm install mongoose."

8. Install cookie-parser: For reading and writing cookies, use the cookie-parser library. Install it with the command "npm install cookie-parser".

9. Install Passport: Passport is an authentication middleware for Node.js. Install it using "npm install passport".

10. Install passport-local: Install the passport-local strategy with "npm install passport-local."

11. Install express-session: Use express-session for managing sessions. Install it by running "npm install express-session".

12. Install connect-mongo: connect-mongo is a MongoDB session store for Connect and Express, written in TypeScript. Install it with "npm install connect-mongo".

13. Install dotenv: To use environment variables from a .env file, install dotenv with "npm install dotenv."

# Prerequisites

1. **System Requirements**:
   - The system should meet basic specifications.
   - Operating System: **Windows**, **Linux**, or **Mac**.

2. **Software Requirements**:
   - Ensure you have an **up-to-date browser** installed.
   - **Node.js installation** is necessary (if you haven't installed it yet, you can download it [here](https://nodejs.org/)).
   - You'll need a **text editor** for code editing, feel free to use your preferred one.

# Technologies Used

- **1. JavaScript**: The primary language used for scripting.
- **2. Node.js** and **Express.js**: For building the server-side application.
- **3. MongoDB**: Utilized as the database management system.
- **4. Passport.js**: Employed for managing user authentication within the application.
- **5. OMDB API**: External API used for retrieving movie data.
- **6. HTML**, **CSS**, and **EJS**: Used for creating the user interface and rendering dynamic content.

# Features
- **1. Sign In** and **Sign Up** functionality provided for user authentication, ensuring secure access to the application.
- **2**. Developed using the **MVC (Model-View-Controller) Architecture**, facilitating a structured and organized codebase.
- **3**. Users can **search for movies** by title and access comprehensive details about each movie.
- **4**. Movie details are **fetched from the OMDB API**, ensuring up-to-date and accurate information.
- **5**. Users have the ability to **add movies to a personal playlist**, enabling them to curate a collection of favorite films.
- **6**. The playlist feature is **private**, ensuring that only the user can access and manage their playlist.
- **7**. While browsing, users can search for movies and view details without signing in, but **adding movies to the playlist** requires authentication to ensure data integrity and user privacy.
