CollegeTrends

CollegeTrends is a student-focused social platform designed to help students discover campus trends, opportunities, communities, and useful information while connecting with other students.

Overview

CollegeTrends brings together student profiles, campus-oriented content, discovery, and social interactions in one platform.

The application is designed around the idea that students should be able to discover what is happening within their university community, share content, connect with other students, and keep track of information relevant to their academic and social environment.

The frontend provides the user-facing experience for interacting with the CollegeTrends platform.

Core Features

- Student registration and authentication interface
- Student profiles
- University and course information
- Personalized student feed
- Post creation
- Image and media sharing
- Comments
- Likes
- Upvotes and downvotes
- Bookmarks
- Following and follower relationships
- Verified-user indicators
- Private-profile support
- Student discovery
- Responsive interface
- Interactive social feed experience

User Experience

Student Profiles

Students can maintain profiles containing information such as their name, username, university, course, biography, avatar, and profile visibility.

Feed

The platform provides a social feed where students can discover posts and interact with content from other users.

Social Interaction

Students can interact with posts through:

- Likes
- Comments
- Upvotes
- Downvotes
- Bookmarks

Users can also follow other students and view their profiles.

Media

The platform supports media-oriented posts and profile avatars, providing students with a richer way to share content and express themselves.

Technology

- HTML5
- CSS3
- JavaScript
- Responsive Web Design
- REST API integration
- Git & GitHub
- Vercel

Architecture

CollegeTrends is structured as a separate frontend and backend application.

                    CollegeTrends
                         │
              ┌──────────┴──────────┐
              │                     │
              ▼                     ▼
        Frontend Application    Backend API
        HTML/CSS/JavaScript     Flask/Python
              │                     │
              └──────────┬──────────┘
                         │
                         ▼
                    PostgreSQL

The frontend is responsible for the user interface and communicating with the backend API for authenticated application functionality.

Project Structure

CollegeTrends/
├── index.html
├── screenshots/
│   └── project screenshots
└── README.md

Related Backend

The backend is maintained in a separate repository and provides authentication, API endpoints, database operations, social interactions, and media handling.

Live Demo

See the repository's deployed application link for the current live version.

Project Status

Frontend MVP / Active Project

CollegeTrends is developed as a broader student-community platform with the frontend and backend maintained independently.

License

See the repository license for applicable usage and distribution terms.