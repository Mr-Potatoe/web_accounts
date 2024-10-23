# Project README

This repository contains the project that utilizes various tools, platforms, and APIs for development and integration. Below is a list of the accounts and services involved in the project setup.

## Accounts and Services

### 1. PlanetScale
   - URL: [PlanetScale Dashboard](https://app.planetscale.com/jaymeajarns/welcome)
   - Description: Used for managing MySQL databases at scale. Ensure the database is connected to the application for seamless database operations.

### 2. Vercel
   - URL: [Vercel Projects](https://vercel.com/mr-potatoes-projects)
   - Description: Vercel is used for hosting and deploying the frontend/backend of the project. Make sure to link the GitHub repository for continuous deployment.

### 3. W3Schools Pathfinder
   - URL: [Pathfinder by W3Schools](https://pathfinder.w3schools.com/)
   - Description: Provides tutorials and learning paths for web development technologies. You can use this to explore various web technologies during development.

### 4. Clarifai
   - URL: [Clarifai General Image Recognition Model](https://clarifai.com/clarifai/main/models/general-image-recognition)
   - Description: Clarifai is used for image recognition features in this project. You can use the general model to integrate image analysis in the application.

### 5. AnyConv
   - URL: [TTF to WOFF Converter](https://anyconv.com/ttf-to-woff-converter/)
   - Description: This tool is used for converting fonts from `.ttf` to `.woff` formats to ensure compatibility for web usage.

### 6. Ngrok
   - URL: [Ngrok Dashboard](https://dashboard.ngrok.com/get-started/your-authtoken)
   - Description: Ngrok is used for securely exposing the local development environment to the web. Use the authtoken from the dashboard to authenticate the tunneling service.

### 7. GitHub Repository
   - URL: [GitHub Repo](https://github.com/Mr-Potatoe)
   - Description: This is the main repository for the project. Ensure all changes are committed and pushed here to keep track of project development and allow for collaboration.

## How to Set Up

1. Database Setup:
   - Log into the [PlanetScale](https://app.planetscale.com/jaymeajarns/welcome) account and configure the database according to the project schema.
   - Update your application’s database connection settings to reflect the PlanetScale credentials.

2. Deployment:
   - Link the project repository to [Vercel](https://vercel.com/mr-potatoes-projects) for automatic deployment.
   - Configure environment variables in Vercel for any sensitive information like database credentials or API keys.

3. Ngrok Configuration:
   - Log in to the [Ngrok Dashboard](https://dashboard.ngrok.com/get-started/your-authtoken) and copy your authtoken.
   - Use the authtoken in your local environment to expose the app to the web.

4. Fonts:
   - Use [AnyConv](https://anyconv.com/ttf-to-woff-converter/) to convert any necessary fonts from `.ttf` to `.woff`.
   - Include these converted font files in the project for local use.

5. Image Recognition:
   - Set up the image recognition functionality using the [Clarifai General Model](https://clarifai.com/clarifai/main/models/general-image-recognition) API. Ensure the API key is configured in your environment.

## Project Structure

- `/src`: Contains the main source code for the application.
- `/public`: Static files including images, fonts, and other resources.
- `/scripts`: Scripts for automating tasks like deployment, database migrations, etc.

## Contribution Guidelines

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit and push your changes.
4. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
