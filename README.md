# Front-end
## Project Overview
    This project is a full-stack clone of the popular accommodation booking platfrom AirBnB. The goal is to build a functional web application that allows users to browse property listings, view detailed property information, and complete bookings. The project will cover frontend development, backend APIs, database design, and deployment


## Tech Stack
- Frontend: React
- Version Control: Git and GitHub
- Design Tools: Figma for UI/UX design

## UI/UX Design Planning.
### Design Goals
- Create intuitive booking flow
- Maintain visual consistency
- Ensure fast loading times
- Prioritize mobile resoponsiveness.

### Figma Design Specifications
#### Color Styles:
- Primary: #FF5A5F
- Secondary: #008489
- Background: #FFFFFF
- Text: #222222
- Secondary Text: #717171

#### Typography:
- Primary Font: Circular, Medium(500), 16px
- Headings: Circular, Bold(700),24px-32px
- Secondary Text: Circular, Book (400), 14px

#### Importance of Identifying design properties
- To ensure accurate implementation when developing, including precise measurement, color codes, typography, assets etc.
- To ensure consistency and a unified system such as design language, creating reusable componet, for team collaboration and efficiency. 

## Key Features
- Property search and filtering
- Detailed property viewing
- Secure checkout process
- User authentication

## Primary pages
|Page | Description |
|:-- | --: |
|Property listing view | Grid display of available properties with filters|
|Listing detailed vies| Complete property details with images and booking form|
|simple checkout| Streamlined payment and booking confirmation|

## Importance of a user-friendly design in a booking system.
A well-designed booking system reduces friction in the user journey, increases conversion rates, and imporves customer satisfaction. Clear navigation, intuitive interfaces, and responsive design are critical for success.

## Project Roles and Responsibilities
|Roles | Responsibilities |
|:-- | --: |
|Project Manager | Oversees timeline, coordinates team, manages deliverables |
|Frontend Developers | Implements UI components, ensures responsive design |
|Backend Developers | Build APIs, manages databases, implements business logic |
|Designers | Create mockups, maintain design system, ensures UX quality |
|QA/Testers | Writes test cases, perform testing, reports bugs|
|DevOps | Manages deployment, CI/CD pipelne, server infrastructure.|
|Product Owner| Defines requirements, prioritizes features, represent stackholers|
|Scrum Master | Facilitates agile processes, removes blockers, organizes meetings|

## UI Component Patterns
#### Planned Components
1. Navbar
- logo
- Search bar
- User navigation
-Responsive menu
2. Property Card
- Proerty image
- Basic details (price, location, rating)
- Favorite button
-Responsive layout
3. Footer
- Site links
- Company information
- Social media links
- Copyright information

Each components will be designed for reusability and consistency accross the application.

# Backend
## Project Overview
The backend for the Airbnb Clone project is designed to provide a robust and scalable foundation for managing user interactions, property listings, bookings, and payments. This backend will support various functionalities required to mimic the core features of Airbnb, ensuring a smooth experience for users and hosts. 

## Project Goals
1. **User management:**
Implement a secure system for user registration, authentication, and profile management.
2. **Property Management:** 
Develop features for property listing creation, updates and retrieval. 
3. **Booking System:**
Create a booking mechanism for users to reserve properties and manage booking details. 
4. **Payment Processing:**
Integrate a payment system to handle transactions and record payment details. 
5. **Review System:** 
Allow users to leave review and ratings for properties. 
6. **Data Optimization**
Ensure efficient data retrieval and storage through database optimizations. 

## Technology Stack
- **Django:** A high level Python web framework used for building the RESTful API.
- **Django REST Framework:** Provides tools for creating and managing RESTful APIs.
- **PostgreSQL:** A powerful relational database used for data storage
- **GraphQl:**  Allows for efficient querying of data
- **Celery:** For handling asynchronous tasks such as sending notifications or processig payments. 
- **Redis:** Used for caching and session management 
- **Docker:** Containerization tool for consistent developemnt and deployment environments. 
- **CI/CD Pipelines:** Automated pipelines for testing and deploying code changes.
