# Vite React 18 Project

## Overview

This is a React 18 application built using Vite. The project utilizes environment variables for API and database configurations.

## Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

## Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/asalwania/mvoie-app.git
   cd mvoie-app
2. **Add Environment Variables**

   Create a `.env.local` file in the root directory of the project and add the following variables:

   ```env
   VITE_TMDB_API_KEY=<your-tmdb-api-key>
   VITE_APPWRITE_PROJECT_ID=<your-appwrite-project-id>
   VITE_APPWRITE_DB_ID=<your-appwrite-db-id>
   VITE_APPWRITE_COLLECTION_ID=<your-appwrite-collection-id>
   ```
3. **Install Dependencies**

   Install the project dependencies by running:

   ```bash
   npm install
   ```

4. **Run the Development Server**

   Start the development server with:

   ```bash
   npm run dev
   ```
   The application will be available at http://localhost:5173.

5. **Build for Production**

   To create a production build of the application, use:

   ```bash
   npm run build
   ```
   The production-ready files will be generated in the `dist` folder.
## Features

- Built with React 18
- Fast and efficient development environment using Vite
- Environment variable configuration for easy API and database management
