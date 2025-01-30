# *Fitness Social Media Platform*

A Project for IT3030 - Programming Applications and Frameworks

## *Project Overview*
This project aims to develop a *social media platform* tailored for fitness enthusiasts. Users can share fitness journeys, workouts, meal plans, and progress updates while interacting with others in a community-driven environment.

## *Key Features*
- *Content Sharing:* Users can upload photos, videos, and descriptions related to fitness.
- *Workout Tracking:* Predefined workout templates for easy tracking.
- *Customizable Workout Plans:* Users can create and share workout plans.
- *Meal Plans:* Categorized meal plans with detailed recipes.
- *User Profiles:* Follow other users, like and comment on posts, and manage personal profiles.
- *Notifications:* Alerts for post interactions.

## *Technologies Used*
- *Backend:* Spring Boot (REST API)
- *Authentication:* OAuth 2.0 (Google, Facebook, Apple)
- *Security:* Spring Security, HTTPS, Input Validation
- *Frontend:* Client Web Application
- *Database:* To be determined (SQL/NoSQL)

## *System Architecture*
The system consists of two main components:
1. *REST API:* Handles authentication, media uploads, post management, interactions, and profile management.
2. *Client Web Application:* Provides a user-friendly interface for accessing all platform functionalities.

## *API Endpoints*
| Endpoint | Method | Description |
|----------|--------|-------------|
| /auth/register | POST | User Registration |
| /auth/login | POST | User Login (OAuth 2.0) |
| /posts | GET | Retrieve all posts |
| /posts/{id} | GET | Get a specific post |
| /posts | POST | Create a new post |
| /posts/{id} | PUT | Update a post |
| /posts/{id} | DELETE | Delete a post |
| /users/{id}/follow | POST | Follow another user |
| /users/{id}/profile | GET | View user profile |

## *Contributors*
- *Perera G.M.T.* (IT21196638) - Meal Plan Management
- *Udana L.M.A.I.* (IT21310614) - Current Workout Status Management
- *Liyanage E.S.T.* (IT21309724) - Workout Plan Management
- *Mahawaththa N.T.M.A.S.M.* (IT21308598) - Post Management
