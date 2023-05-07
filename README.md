
# ReSolved 

This is a social media app clone inspired by Quora. Users can create posts in various categories and other users can respond with comments, upvotes, and downvotes.

## Low Level System Diagram 

![Image Description](https://drive.google.com/uc?export=view&id=1kw2RR2HAG5d6IN7a7gL6QWS_dNWW5UNg)

## Features 

### 1. Login / Register
  + **User Registration**: Users can create a new account by providing their details such as name, email, and password.
  + **User Login**: Registered users can log in to their accounts using their credentials.
### 2. Posting Questions
+  **Ask a Question**: Users can post a question by providing a title, description, and relevant tags to categorize it.
+  **Categorization**: Questions can be organized into different categories or topics to help users navigate and filter content more effectively.
 
### 3. Answering Questions
+ **Answer a Question**: Users can provide answers to questions posted by others, including a description and optional attachments.
+ **Commenting**: Users can leave comments on questions or answers to provide additional information, clarification, or engage in discussions.

### 4. Chat Functionality
+ **Direct Messaging**: Users can send private messages to other users for one-on-one conversations or further discussions.

### 5. Search
+ **Search by Keywords**: Users can search for questions or users based on keywords, tags, or specific terms.
 
## Features

### 1. Unique User Verification 
- User interface for users to register and log in.

- User profiles with profile pictures and bio.
- Post creation with max character limit of 2000
- Commenting on posts 
- User tagging in responses
- Upvoting and downvoting posts and comments
- Home page listing posts with highest upvotes based on categories
- Categories including Technology, Lifestyle, Politics, Food, Economics, Sports, etc.
- Direct messaging between users


## Technologies Used

- React: Frontend framework
- Node.js: Backend runtime environment
- Express: Backend framework
- Firebase: Backend as a service and cloud storage provider

## Setup

1. Clone the repository
2. Navigate to the root directory and run `npm install` to install the necessary dependencies.
3. Create a Firebase project and setup `FireStore DB` , `Storage Bucket` and `Authentication` with the Firebase configuration credentials.
4. Create a `firebaseConfig.js` file in the `src` directory with the following environment variables:
   - `REACT_APP_API_KEY`: Firebase API key
   - `REACT_APP_AUTH_DOMAIN`: Firebase auth domain
   - `REACT_APP_PROJECT_ID`: Firebase project ID
   - `REACT_APP_STORAGE_BUCKET`: Firebase storage bucket
   - `REACT_APP_MESSAGING_SENDER_ID`: Firebase messaging sender ID
   - `REACT_APP_APP_ID`: Firebase app ID
 5. Run `npm start` to start the development server.

## Contributors
  - [Dron Rahangdale](https://github.com/Drontitan)
  - [Vedang Dadape](https://github.com/Vedang12d)
  - [Darshan Kasar](https://github.com/drshn-k)
  - [Mukesh Tandale](https://github.com/d093w1z)
  - [Ketan Sarode]
  - [Dhiraj Patil]
  - [Parth Jaiswal]
  

## Contributing

Contributions are welcome! Feel free to open a pull request or submit an issue.

## Future Enhancements

- Implement notifications for new comments, upvotes, and direct messages.
- Add more categories for posts.
- Implement moderation features for managing posts and comments.
- Adding a feature for users to create private groups or communities for more focused discussions.
- Implementing a notification system to alert users of new responses or comments on their posts.
- Adding a feature for users to create polls or surveys for community feedback.

<!-- 
# Resolver

####    Resolver is an innovative online platform designed to help users find solutions to their queries and challenges. Inspired by the concept of problem-solving, Resolver aims to provide a space where individuals can seek answers, guidance, and assistance from a community of knowledgeable individuals. -->



<br>

<!-- # User Management -->



<br>

<br>

# Post 
<p align="justify">
Resolver's post feature allows users to share thoughts, questions, and insights with the community. Posts can include text, images, code snippets, and links. Users can leave comments, providing feedback and initiating discussions. The unique tagged comments feature organizes discussions by specific topics. Notifications keep users engaged, and the search function helps users find relevant posts and discussions. Resolver fosters collaboration, knowledge sharing, and problem-solving within its vibrant community.
  </p>

<br>

<br>


# Profile
#### User Profile:
<p align="justify">
Each user on Resolver has a profile that showcases their information, activity history, and contributions within the community. The profile serves as a personal space where users can express their expertise, interests, and engagement.
</p>

#### Follow Functionality:
<p align="justify">
Users can follow other users on Resolver to stay updated with their activities and contributions. By following a user, their posts, comments, and interactions will appear in the follower's feed or notifications. This feature facilitates networking, knowledge sharing, and building connections within the community.
</p>

#### Avatar Creation for Profile Picture:
<p align="justify">
Resolver offers users the ability to create an avatar for their profile picture. Users can personalize their profile by selecting or creating a custom avatar that represents their identity or brand. The avatar creation feature may include options such as choosing different facial features, hairstyles, accessories, and color schemes. This enhances user engagement and allows for creative expression while maintaining a consistent visual presence across the platform.
 </p>

<br>

# Acknowledgements
We would like to acknowledge the following resources and libraries that have been instrumental in building Resolver:

+ Firebase (https://firebase.google.com)
+ React (https://reactjs.org)
+ React Router (https://reactrouter.com)
+ Material-UI (https://mui.com)
