# Backend Development Template  

This repository serves as a starting point for backend development projects. Originally created during my studies in the "Software Backend Development" subject, I’ve converted it into a reusable template. It’s designed to help developers quickly set up and begin their backend projects.  

## Features  
- Pre-configured setup for a backend server.  
- Built with popular frameworks and tools.  
- Simple and easy-to-understand code structure.  

## Tech Stack  
- **Node.js**: JavaScript runtime for building server-side applications.  
- **Express.js**: Lightweight and flexible web framework.  
- **MongoDB**: NoSQL database for efficient data management.  

## Other Tools  
- **Postman**: API testing and development.  
- **Swagger**: API documentation and design.  

## User Authentication & Authorization  
The template includes middleware for user authentication and role-based authorization.  

### Authentication Middleware  
- **Protect Middleware**: Verifies the user's JWT, decodes it, and attaches the user object to the `req` object for further use.  
- **Authorization Middleware**: Restricts access to routes based on user roles (e.g., `admin`, `user`).  

### Edit Configuration
in config/config.env
