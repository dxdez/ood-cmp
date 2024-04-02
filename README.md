# Classic Meal Picker

The Classic Meal Picker is a prototype application developed using React and JSX components. Its primary purpose is to provide a simple interface for users to explore classic meal options, perform searches, and create custom picks for favorite meals. 

The data source for this application comes from [themealdb.com](https://www.themealdb.com/ "themealdb.com") which supports a helpful list of popular meals. Additional functionality from this api includes search and random picks which are used in this application. 

This application was designed from a sample tutorial for experimental purposes and for testing front-end components with an API. You can try this application by visiting the following link [here](https://classic-meal-picker.netlify.app/ "here").

## Basic Features
- Explore classic meal options presented within the application.
- Utilize the search functionality to find specific meals.
- Create custom picks for your favorite meals.

## Running the Application

### Prerequisites
Ensure you have Docker installed on your system.

### Build the Docker Image
- Open your terminal and navigate to the directory containing your React app and the Dockerfile.
- Run the following command to build a Docker image:
```bash
docker build -t classic-meals .
```

### Run Your Docker Container
- Once the Docker image is built successfully, you can run a Docker container based on this image with the following command:
```bash
docker run -p 5173:5173 classic-meals
```
- This command maps port 5173 inside the container to port 5173 on your local machine, enabling access to the application through your browser.
- You should also see the container running in your Docker Desktop app.

### Access the Dockerized React App
- Open your preferred web browser.
- Navigate to [http://localhost:5173](http://localhost:5173).
- You should now be able to interact with the Classic Meal Picker application in your browser.

