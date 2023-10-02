## Overview 

This project involves the creation of a Progressive Web Application (PWA) text editor that operates within web browsers. The application enables users to create and store notes or code snippets, both online and offline, with reliable data retrieval capabilities. It utilizes IndexedDB for data storage, ensuring data persistence even in offline scenarios. The application also integrates a service worker and Cache API to maintain full functionality without an active internet connection.

## Project Links
GitHub Repository: Text Editor
Deployed Application: 

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)

## Installation

To set up this text editor, follow these steps:

1. **Prerequisites:**

   - Ensure you have [Node.js](https://nodejs.org/) installed on your system.

2. **Install Dependencies:**

   - Open your terminal.

   - Navigate to the project directory.

   - Run the following command to install the required npm packages:

     ```bash
     npm install
     ```

   - This command will install the necessary dependencies listed in the project's `package.json` file.

3. **Start the Application:**

   - After installing the dependencies, you can start the application by running:

     ```bash
     npm run start
     ```

   - This command will start the backend server and serve the client.

4. **Ready to Use:**

   - Your text editor is now ready to use! You can access it through your browser.

Please ensure that you have Node.js installed and follow the steps above to set up the text editor.
 

## Usage

1. **Folder Structure**
   
   - Open the text editor web application in your code editor to view the client-server folder structure.

   ![alt text](/assets/images/T1.png)

2. **Running the Application**
   
   - Execute `npm run start` from the project's root directory in your terminal to start the backend server and serve the client.
   
   - This command also bundles JavaScript files using webpack and generates HTML, service worker, and manifest files.

   ![alt text](/assets/images/T2.png)

3. **JavaScript Compatibility**
   
   - The text editor is compatible with next-gen JavaScript, ensuring it functions in the browser without errors.
   
   - Simply open the text editor to use its features.

   ![alt text](/assets/images/T3.png)

4. **IndexedDB Integration**
   
   - IndexedDB immediately creates a database storage.
   
   - Enter content in the text editor, and it will be saved in IndexedDB.
   
   - When you reopen the text editor after closing it, your content is retrieved from IndexedDB.

   ![alt text](/assets/images/T4.png)

5. **Installing as a Desktop App**
   
   - Click the "Install" button to download the web application as an icon on your desktop.

   ![alt text](/assets/images/T5.png)