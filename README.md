# Social Media API
## pet_project_social_media_api

### Description:
RESTful API for social media platform.
The API allows users to create profiles, follow other users, create and retrieve posts,
manage likes and comments, and perform basic social media activities.

### 1. Capabilities:
1. User Registration and Authentication:
2. Users are able to register with their email and password to create an account.
3. Users have the ability to log in using their credentials and receive an authentication token.
4. Users have the ability to log out and cancel their token.

### 2. User Profile:
1. Users shall be able to create and update their profile, including a photo, biography, and other data.
2. Users should be able to receive information about their profile and view other users' profiles.
3. Users should be able to search for users by username or other criteria.

### 3. Follow/Unfollow:
1. Users should be able to follow and not follow other users.
2. Users should be able to view a list of users they are following and a list of users who are following them.

### 4. Creating and searching for posts:
1. Users should be able to create new messages with text content and optional multimedia attachments (e.g., images). (Adding images is an optional task).
2. Users should be able to receive their own messages and messages from users they follow.
3. Users should be able to retrieve posts by hashtags or other criteria.

### 5. Likes and comments (optional):
1. Users should be able to mark posts with "likes" and "dislikes". Users should be able to view a list of posts they have liked. Users should be able to add comments to posts and view comments on posts.

### 6. Scheduling post creation with Celery (optional):
Adds the ability to schedule post creation (you can choose when to create a post before creating it).

### 7. API Permissions:
1. Only authorized users should be able to perform actions such as creating posts, likes, follow/unfollow users.
2. Users should only be able to update and delete their own posts and comments.
3. Users should only be able to update and delete their profile.

### 8. API Documentation:
1. The API should be well documented with clear instructions on how to use each endpoint.
2. The documentation should include sample requests and responses for different API endpoints.


## Technical Requirements:
* Django and the Django REST framework should be used to create the API.
* Use token-based authentication to authenticate users.
* Use appropriate serializers to validate and present data.
* Use appropriate views and view sets to perform CRUD operations on models.
* Use appropriate URL routing for different API endpoints.
* Use appropriate permission and authentication classes to implement API access rights.
* Follow best practices for designing and documenting RESTful APIs.

### Note:
This assignment does not require you to implement a frontend interface. 
Focus on creating a well-structured and documented RESTful API using Django and the Django REST framework. 
This assignment will test a novice DRF developer's skills in building a RESTful API, working with authentication and permissions, working with models, serializers, views and view sets, and following best practices for designing and documenting APIs.
