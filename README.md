# Barangay Management System

This project is a Barangay Management System built with React Vite. It helps manage various tasks and provides real-time data with easy-to-use features.

## Live Demo

Check out the system here: [Barangay Management System](https://barangay-santa-ines.netlify.app/)

## Features

- **Real-Time Data**: Get instant updates on barangay activities and posts.
- **SMS Notifications**: Send SMS messages directly from the app.
- **User Authentication**: Secure login for users and admins using Firebase, including:
  - **Error Handling**: Shows specific error messages for signup and login issues.
  - **Forgot Password**: Users can request a password reset link via email.
- **Weather Updates**: Display current weather information for the barangay.
- **Custom Loading Animations**: Unique loading animations for a better user experience.
- **Certificate Management**:
  - Users can request and update certificate information.
  - Search for certificates.
  - Users receive notifications about the success or failure of their certificate requests.
- **Admin Dashboard**:
  - View real-time updates on barangay activities.
  - Graphs showing payment data (via GCash or cash).
  - Manage pending and approved requests.
  - Create different types of reports.
  - Admin notifications for success or error messages.
  - Logs to track admin activities and manage timeouts.

## Tech Stack

- **Frontend**: React.js Vite and Sass
- **Backend**: Firebase (for database, storage, and authentication)
