# Angular Installation

### 1. Install Node.js and npm
- Make sure you have Node.js and npm (Node Package Manager) installed. 
- You can download and install them from the browser. 
- After installation, check if they are properly installed by running the following commands in your terminal:
```shell
  node version : node -v
  npm version :  npm -v
```
### 2. Install the Angular CLI
- The Angular Command Line Interface (CLI) makes it easier to create and manage Angular projects.
- Install the CLI globally using npm:
```shell
  npm install -g @angular/cli
```   
- After installation, you can verify it with:
```shell
  ng --version
```

### 3. Create a New Angular Project
- Use the Angular CLI to generate a new project by running:
```shell
 ng new my-angular-app
```
- During the setup, you will be prompted with some options such as routing configuration and style format (CSS, SCSS, etc.). You can choose based on your project requirements.

### 4. Navigate to Your Project Folder
- Once the project is created, navigate to the folder:
```shell
cd my-angular-app
```

### 5. Serve the Application
- Start the development server by running:
```shell
  ng serve
```
By default, the app will be served at http://localhost:4200. You can open this in your browser to see your app in action.


