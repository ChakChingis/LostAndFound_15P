﻿# Lost and Found Web Application

## Introduction
This project is a web-based platform designed to help users report, track, and manage lost and found items efficiently. Users can quickly list items they've lost or found, facilitating a smoother recovery process.

## Problem Statement
Losing personal belongings is a common and stressful experience, often resulting in significant inconvenience and emotional distress. Current solutions for reporting and recovering lost items tend to be fragmented and inefficient, leading to delays and a low recovery rate. This application addresses these issues by providing a centralized, user-friendly platform to report and track items in real-time, improving communication and coordination between finders and owners, thereby increasing the likelihood of items being returned promptly.

## Objectives
- To provide a centralized platform for managing lost and found items.
- To facilitate real-time updates and easy communication between item finders and owners.
- To enhance user experience through an intuitive and responsive interface.

## Technology Stack
- **Frontend:** ReactJS
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Others:** Axios, Bootstrap, React Router

## Installation Instructions
Follow these steps to set up and run the application locally:

### Step 1: Clone the Repository
```bash
git clone https://github.com/ChakChingis/LostAndFound_15P.git
```

### Step 2: Navigate to Project Directories
Navigate into backend and frontend directories separately and install dependencies:

#### Backend:
```bash
cd LostAndFound_15P/src/Lost_and_Found_back
npm install
```

#### Frontend:
```bash
cd LostAndFound_15P/src/lost-and-found
npm install
```

### Step 3: Start the Applications

Start the backend server first:
```bash
cd backend
npm start
```

Then, start the frontend application:
```bash
cd frontend
npm start
```

Ensure the backend is running before starting the frontend to allow successful communication between both applications.

## Usage Guide
Users can interact with the application by:
- Reporting lost or found items through the web interface.
- Viewing real-time updates on items reported by other users.
- Communicating directly with other users to arrange item recovery.

Upon accessing the application, users are first prompted to either register using their email address or log in if they already have an account. After authentication, users are directed to the main page where they can browse listed lost and found items. They can apply filters to easily find specific items, add new lost or found items, and manage their own submissions. Additionally, users have a profile section where they can view the items they have added, update item details, and edit their personal information.

## Team Members
Baiyrbek Perizat 15-P
Bimanov Chingis 15-P
Tursynova Aliya 15-P
Mukhanbetzhanova Aruzhan 17-P
Satypaldy Askhat 20-P
Suieubek Nurbek 20-P

