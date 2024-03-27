# Workout Tracker App

This is a MERN (MongoDB, Express.js, React.js, Node.js) application for tracking workouts. Users can enter the type of workout, weights in kilograms, and the number of reps for each exercise.

## Technologies Used

- React.js
- Context API for state management
- Node.js with Express.js for backend
- MongoDB for database

## Setup Instructions

1. Clone the repository:
   git clone [https://github.com/blvck-code/MERNapp.git](https://github.com/blvck-code/MERNapp.git)
2. Navigate to the project directory:
   cd workout-tracker
3. Install dependencies:
   npm install
4. Set up MongoDB:
- Make sure MongoDB is installed and running on your system.
- Create a `.env` file in the root directory of the project and add your MongoDB URI:
  ```
  MONGO_URI=your_mongodb_uri_here
  ```
5. Start the server:
   npm start
6. Navigate to `http://localhost:3000` in your browser to view the app.

## Folder Structure

- `client`: Contains the React.js frontend code.
- `server`: Contains the Node.js with Express.js backend code.

## Features

1. **Add Workout Entry**: Users can enter the type of workout, weights in kilograms, and the number of reps for each exercise.
2. **View Workout History**: Users can view their workout history with details of each exercise.
3. **Edit/Delete Entries**: Users can edit or delete existing workout entries.
4. **Responsive Design**: The app is designed to be responsive and accessible on various devices.

## API Endpoints

- `GET /api/workouts`: Get all workout entries.
- `POST /api/workouts`: Add a new workout entry.
- `PUT /api/workouts/:id`: Update an existing workout entry.
- `DELETE /api/workouts/:id`: Delete a workout entry by ID.

## Technologies Used

- **Frontend**:
- React.js
- Context API
- Axios (for API requests)
- Bootstrap or Material-UI (for styling)
- **Backend**:
- Node.js
- Express.js
- MongoDB (with Mongoose for object modeling)
- **Development Tools**:
- npm (Node Package Manager)
- Git and GitHub for version control

## Future Improvements

1. User authentication and authorization.
2. Ability to categorize workouts (e.g., strength training, cardio, etc.).
3. Graphical representation of workout progress.
4. Integration with fitness APIs for additional data tracking.
