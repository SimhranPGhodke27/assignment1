# Greet Users App

This README provides instructions for setting up and running the Greet Users application. Follow the steps below to get the project up and running on your local machine.

## Instructions

1. **Create a Project Directory**
   - Create a folder named `greet-users-app` in your local directory.

2. **Download Repository Files**
   - Download all the files from this repository into the newly created folder (`greet-users-app`).

3. **Open Command Prompt**
   - Open Command Prompt on your computer.

4. **Change Directory to Project Folder**
   - Navigate to the project directory by using the following command:

     ```bash
     cd your\projectdirectory\greet-users-app
     ```

5. **Run the API Server**
   - Enter the `myapi` folder directory:

     ```bash
     cd myapi
     ```

   - Run the following command to start the API server.

     ```bash
     go run main.go
     ```
  - You should see the message: `Server is running on http://localhost:8080`.
    
6. **Open Project in VSCode**
   - Open the `greet-users-app` folder in Visual Studio Code (VSCode) and open the terminal within VSCode.

7. **Start the Angular Application**
   - In the VSCode terminal, run the following command:

     ```bash
     ng serve
     ```

   - This will launch the Angular application on a local server.

8. **View the Application**
   - Click on the link provided in the terminal to view the application in your web browser. Reload the page as needed.

9. **Verify User List Display**
   - You should see the user list displayed in the middle column. This list is provided by the API running on `localhost:8080`.

10. **Exit the Application**
    - To exit the Angular application, simply close the browser window.

11. **Stop the API Server**
    - To stop the API server, press `Ctrl+C` in the Command Prompt where the server is running.

# GreetUsersApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
