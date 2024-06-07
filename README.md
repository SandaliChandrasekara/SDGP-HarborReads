## HarborReads

HarborReads is a web application designed to provide personalized book recommendations to beginner readers through a chatbot-driven interface. The platform includes various features such as a user-friendly chatbot, personalized user profiling, a personal library, reading insights, challenges and quizzes, and book previews.

## Features

Chatbot (Core): Provides book recommendations through an interactive chatbot interface.
User Profiling: Collects and stores user data to personalize recommendations.
Personal Library: Allows users to manage and keep track of their reading lists.
Reading Insights: Offers insights into reading habits and progress.
Challenges and Quiz: Engages users with reading challenges and quizzes.
Book Preview: Provides previews of recommended books.

## Tech Stack

Frontend Development: React.js
Backend Development: Node.js with Express
Chatbot Development: OpenAI / Cosine Similarity
Deployment: Docker, Google Cloud Platform (GCP), GitHub Actions
API Testing: Postman
Database Management: MongoDB

## Chat Types

Static questions were defined for different chat types such as new readers, avid readers, and book chats. The questions are designed to understand users' reading preferences and experiences.

## User Data

User data is collected from user profiling to enhance the personalization of book recommendations.

## Getting Started

## Prerequisites

Make sure you have the following installed:

Node.js
npm
Docker (for deployment)

## Clone the Repository

git clone [https://github.com/Sa/harborreads.git](https://github.com/SandaliChandrasekara/SDGP-HarborReads.git)
cd harborreads

## Running the Backend

Navigate to the backend directory and start the server:

cd backend
npm install
node app.js
The backend will run on port 3001.

## Running the Frontend

Navigate to the frontend directory and start the development server:

cd frontend
npm install
npm run dev
The frontend will run on port 5173.

## Deployment

For deployment, you can use Docker and Google Cloud Platform (GCP). GitHub Actions are configured for continuous integration and deployment.

## API Testing

Postman is used for API testing. Ensure you have Postman installed to test the API endpoints.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
If you have any questions or suggestions, feel free to reach out to the project maintainers.

Happy Reading with HarborReads!







