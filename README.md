# E-Commerce Website

# E-Commerce Frontend - React.js Project
This project is a React.js-based frontend for an e-commerce platform. It provides a dynamic and responsive user interface for seamless shopping experiences.

## Features
- **React.js Framework:** Component-based UI development for better reusability.
- **HTML, CSS, JavaScript:** Core web technologies for styling and interactivity.
- **REST API Integration:** Connects with the backend to fetch and manage data.
- **React Router:** Enables client-side routing for a seamless navigation experience.
- **Redux (Optional):** Manages global state for cart, authentication, and UI state.
- **Responsive Design:** Ensures a smooth experience across all devices.

## Prerequisites
Ensure you have the following installed:
- Node.js (version 14 or higher)
- VS Code (or any preferred code editor)
- A running instance of the E-Commerce Backend

## Installation and Setup
### 1. Clone the repository
```bash
git clone https://github.com/Spidy111/E-commerce-website.git
cd E-commerce
```
### 2. Install dependencies
```bash
npm install
```
### 3. Configure Environment Variables
Create a `.env` file in the root directory and set the required environment variables:
```bash
REACT_APP_API_BASE_URL=<Your Backend API URL>
REACT_APP_RAZORPAY_KEY=<Your Razorpay Public Key>
```

#### 4. Run the application
Start the development server:
```bash
npm run dev
```
The application will be available at `http://localhost:3000`.

## Build and Deploy
Build the Application
```bash
npm run build
```
The optimized build files will be generated in the build directory.

## Deploying to Production
You can deploy the built project to any static hosting service like:
- Vercel
- Netlify
- Amazon S3 + CloudFront
- Firebase Hosting

## Resources
- React.js Documentation
- React Router
- Redux Documentation
- CSS Flexbox & Grid Guide


# E-Commerce Backend - Spring Boot Project

This project is a Spring Boot-based backend service for an e-commerce platform. It uses MySQL for data storage, Amazon S3 for file storage, and Razorpay for payment processing.

## Features

- **Spring Boot Framework:** Simplified development with preconfigured components.
- **MySQL Integration:** Relational database management with Hibernate ORM.
- **Amazon S3 Integration:** Storage of media files and other assets.
- **Razorpay Payment Gateway:** Secure payment handling.
- **Maven Build System:** Dependency management and project configuration.

## Prerequisites

Ensure you have the following installed:

- [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html) (version 8 or higher)
- [Apache Maven](https://maven.apache.org/) (version 3.6 or higher)
- [MySQL](https://www.mysql.com/) (version 5.7 or higher)
- AWS account for S3 configuration
- Razorpay account for payment integration

## Configuration

Update the following properties in the `application.properties` file:

### Replace placeholders with:
- `{YourDatabaseName}`: Name of your MySQL database
- `{databaseUsername}`: Your database username
- `{databasePassword}`: Your database password
- `{bucketName}`: Your S3 bucket name
- `{S3BucketRegion}`: AWS region of your S3 bucket
- `{accessKey}`: Your AWS access key
- `{secretKey}`: Your AWS secret access key
- `{razorpayTestKey}`: Your Razorpay test key
- `{razorpayTestSecret}`: Your Razorpay test secret

## Running the Application

### 1. Clone the repository
```bash
git clone https://github.com/Spidy111/E-commerce-website.git
cd <project_directory>
```

### 2. Build the project
Use Maven to build the project:
```bash
mvn clean install
```

### 3. Run the application
Start the application using:
```bash
mvn spring-boot:run
```

The application will run on `http://localhost:8081`.

## Build and Deploy

### Package the Application
Create a JAR file for deployment:
```bash
mvn package
```
The JAR file will be located in the `target` directory.

### Deploy the JAR
Run the JAR file:
```bash
java -jar target/<your-application-name>.jar
```

## Resources

- [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- [Hibernate Documentation](https://hibernate.org/)
- [MySQL Documentation](https://dev.mysql.com/doc/)
- [AWS S3 Documentation](https://aws.amazon.com/s3/)
- [Razorpay Documentation](https://razorpay.com/docs/)
