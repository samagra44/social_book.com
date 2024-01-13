# Social Book - A Social Media Platform

## Project Overview

Social Book is a social media platform inspired by popular platforms like Instagram and Facebook. It allows users to connect with others, share posts, follow other users, like posts, download images, and make user suggestions. This README provides an overview of the project's structure, features, and usage instructions.

## Table of Contents

1. [Installation](#installation)
2. [Features](#features)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

## Installation

To run Social Book on your local machine, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/samagra44/social_book.git
   cd social_book
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. Install project dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```
   python manage.py migrate
   ```

5. Create a superuser for admin access:
   ```
   python manage.py createsuperuser
   ```

6. Start the development server:
   ```
   python manage.py runserver
   ```

7. Open your web browser and navigate to `http://localhost:8000` to access the Social Book application.

## Features

### User Authentication

- **Signup and SignIn:** Users can create accounts by signing up with their email addresses or social media accounts. They can also log in using their credentials.

- **Account Settings:** Users can manage their profile information, including changing their profile picture, username, and password.

### Posting and Feeds

- **Uploading Posts:** Users can upload images along with captions to share with their followers.

- **Post Feed:** The home page displays a feed of posts from the users that the logged-in user follows.

- **Like Posts:** Users can like posts, and the number of likes is displayed on each post.

- **Download Images:** Users can download images from posts they are interested in.

### User Interactions

- **Follow and Unfollow Users:** Users can follow other users to see their posts in their feed. They can also unfollow users.

- **Profile Page:** Each user has a profile page displaying their posts and follower/following counts.

- **Post Feed Updates:** The feed updates in real-time when users they follow post new content.

### Discover and Search

- **Search User:** Users can search for other users by their usernames.

- **User Suggestions:** Users receive suggestions for other users to follow based on their activity and interests.

## Usage

1. **Signup and Login:** To get started, create an account by signing up. If you already have an account, log in using your credentials.

2. **Profile:** Customize your profile by uploading a profile picture and updating your username.

3. **Posting:** Share your posts by clicking the "Upload" button on your profile page. Add an image and a caption.

4. **Feeds:** View posts from users you follow on your home page. Like and download posts as you wish.

5. **Interact:** Follow or unfollow other users to curate your feed. Check out their profiles for more content.

6. **Discover:** Use the search functionality to find other users by their usernames. Receive user suggestions to expand your network.

## Contributing

We welcome contributions to Social Book! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Create a pull request with a clear description of your changes.

---
Feel free to customize it further to provide more specific details or instructions based on your project's needs.      

![Sign In - Social Book - Brave 2024-01-13 22-45-56](https://github.com/samagra44/social_book.com/assets/77968722/5554d270-2c6c-4019-958b-3a2beb31ec24)
