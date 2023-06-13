
**Features Description:**
1. File Upload: This feature allows users to upload new files to the file manager. Users can either click on a button or drag and drop files into the designated area. Once a file is uploaded, it is added to the `myFiles` array in the app's state and displayed in the file manager.

2. File Search: The search functionality enables users to search for specific files within the file manager. Users can enter keywords or file names in the search input field, and the displayed files are dynamically filtered based on the search query. This allows users to quickly find files based on their names or specific keywords.

**Reason for Choosing the Features:**
These two features are essential additions to the Multimedia Web App for the following reasons:
- File Upload: It empowers users to personalize the app by uploading their own files and managing them within the app. This enhances the app's functionality and allows users to have a more personalized experience.

- File Search: As the file manager grows with more files, finding specific files can become challenging. The search feature improves the usability of the app by enabling users to quickly locate files based on their names or relevant keywords. It saves time and enhances user productivity.

**Code Explanation:**
The provided code implements the File Upload and File Search features. The File Upload functionality is added by including a button and an input field of type "file" in the UI. When the user selects a file, the `handleFileUpload` function is triggered, creating a new file object with a unique ID, name, path, and type. The new file is added to the `myFiles` array using the `setMyFiles` function.

The File Search functionality is implemented by including an input field for users to enter search queries. The `searchQuery` state variable is updated based on user input. The displayed files are dynamically filtered by mapping through the `myFiles` array and checking if the file's name or type matches the search query. The filtered files are then displayed in the file manager.

These features enhance the app by allowing users to manage their own files and quickly find specific files based on their names or keywords, making it a more user-friendly and efficient multimedia web application.


# Getting Started with Create React App

This project was bootstrapped with [Create React App].

## Available Scripts

In the project directory, you can run:

### `npm install react-chartjs-2`

This command downloads and installs the react-chartjs-2 package. This package allows us to draw beautiful graphs and charts on React Web Application.

### `npm run start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!
 



