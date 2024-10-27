# ShishuVani-E-Learning-Website

It`s a Full Stack Development project using MEAN Stack.

<img src="home.png">

### Steps to Set Up an Angular Environment with Conda and Node.js

1. Create a Conda Environment with Node.js: Use the following command to create a Conda environment named env_name and install Node.js version 18 from the conda-forge channel:

```
conda create -n env_name -c conda-forge nodejs=18
```

2. Activate the Conda Environment: Once the environment is created, activate it to use the installed Node.js version:

```
conda activate env_name
```

3. Install Angular CLI Globally: Install the Angular CLI globally within the environment using npm. This will allow you to create and manage Angular projects:

```
npm install -g @angular/cli
```

4. Create or Navigate to Your Angular Project:

If you haven't created an Angular project yet, create a new one by running:

```
ng new project-name
```

5. If you already have an Angular project, navigate to its directory:

```
cd path/to/your-angular-project
```

6. Run the Angular Application: Start the development server with the following command, which will launch the app on http://localhost:4200 by default:

```
ng serve
```

7. Open the Application in a Browser: Visit http://localhost:4200 in your web browser to view the running Angular application.
