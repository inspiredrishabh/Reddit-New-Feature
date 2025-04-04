# Project Setup Guide

Follow these steps to get started with this project:

### Step 1: Fork the Repository
1. Click on the **Fork** button in the top-right corner of this repository page.
2. Select your GitHub account to create a copy of the repository.

### Step 2: Clone the Repository
1. Open your terminal/command prompt.
2. Run the following command to clone the forked repository to your local machine:
   ```bash
   git clone https://github.com/inspiredrishabh/Reddit-New-Feature.git
### Step 3: Navigate to the Project Directory
Move into the project directory by running:

  ```bash
  cd Reddit-New-Feature
  ```
### Step 4: Install Dependencies
Run the following command to install all necessary dependencies:

  ```bash
  npm install
 ```
### Here's the folder structure : 

```
src/
├── components/
│   ├── CommunityChat/
│   │   ├── ChatPage.jsx
│   │   ├── ChatBox.jsx
│   │   ├── ChatList.jsx
│   │   ├── MessageInput.jsx
│   │   └── styles.css
│   ├── Shared/
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   └── Sidebar.jsx
│   └── HomePage.jsx
├── context/
│   ├── ChatContext.jsx
│   ├── AuthContext.jsx
│   └── CommunityContext.jsx
├── pages/
│   ├── Home.jsx
│   ├── CommunityChat.jsx
│   └── CommunityList.jsx
├── utils/
│   ├── api.js
│   └── helpers.js
├── assets/
│   └── images/
├── App.jsx
├── index.js
└── styles.css
```
