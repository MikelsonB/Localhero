# LocalHero
This repository contains the code for our LocalHero website, created for the SOEN-357 course.

## How to Run the Project
Follow the steps below to run the project on your local machine:

1. Create a .env File
At the root level of the project (inside the LocalHero folder), create a .env file and add the following code inside it:

NEXTAUTH_URL=http://localhost:3000/
NEXTAUTH_SECRET=mytestApp
This configuration is necessary for the authentication system to work properly.

2. (Optional) Configure MongoDB URI
If you'd like to use your own MongoDB database, open the conn.js file located at:

LocalHero/backend/database/conn.js
Change the value of MONGO_URI to your MongoDB URI. By default, it connects to our online database, but you can replace it with your own database connection string if needed.

3. Install Dependencies
Open your terminal and navigate to the project directory. Run the following command to install all necessary dependencies:

npm install

This will download all the required libraries and packages for both the frontend and backend.

5. Start the Development Server
After installing the dependencies, run the following command to start the development server:

npm run dev

This will start the application on your local machine, and you can access it at:

http://localhost:3000/
The development server will automatically reload as you make changes to the code.

5. Access the Platform
Open your web browser and go to http://localhost:3000/ to view and interact with the platform.


## Technologies Used & Approach

- [Next.js 13](https://nextjs.org/docs/getting-started): Web development framework used with React that provides Server Side Rendering
- [NextUI v2](https://nextui.org/): CSS library built on top of tailwind to add extra stylings to website
- [Tailwind CSS](https://tailwindcss.com/): CSS library that helps styling the website
- [Tailwind Variants](https://tailwind-variants.org): CSS library extension for tailwind
- [ReactJS](https://www.typescriptlang.org/): Frontend library to facilitate creation of website
- [NodeJS](https://nodejs.org/en/): Backend
- [Mongoose](https://mongoosejs.com/docs/): Backend database used to store different values for users, properties, etc.
