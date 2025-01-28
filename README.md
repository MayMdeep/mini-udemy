# E-Learning Platform (Mini Udemy)

An online learning platform where instructors can create, manage, and sell courses, while students can browse, enroll, and track their progress.

## Features

### User Roles
- **Student**: Browse/enroll in courses, track progress, submit assignments.
- **Instructor**: Create/edit courses, upload videos, manage quizzes, view earnings.
- **Admin**: Manage users, moderate content, handle disputes.

### Authentication
- **Email/Password login**
- **Google/GitHub OAuth**
- **JWT for session management**

### Course Management
- **Instructor Dashboard**: Create courses, upload video lectures, add quizzes.
- **Course Preview**: Free preview lessons.
- **Monetization**: One-time purchases and subscription tiers.

### Interactive Learning
- **Quizzes & Assignments**: Auto-grade multiple-choice quizzes, peer-reviewed coding assignments.
- **Discussion Forums**: Real-time Q&A for each course.

### Payment Integration
- **PayPal and Stripe** for payments.
- Revenue split: Platform takes 15% commission.

### Admin Panel
- Dashboard for users, courses, and revenue metrics.
- Ability to suspend abusive accounts or content.

### Content Delivery
- **Video Streaming**: Uses AWS S3 or Cloudinary for storage and streaming.
- **Downloadable Resources**: Allow students to download course materials.
- **Progress Tracking**: Save watched lessons and quiz scores.

## Tech Stack

- **Frontend**: Next.js, Redux for state management, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB, PostgreSQL
- **Video Streaming**: AWS S3, CloudFront, or Mux
- **Search**: ElasticSearch
- **Testing**: Jest (unit), Cypress (E2E)

## Advanced Features (Optional)

- **Live Classes**: Use WebRTC for live instructor Q&A sessions.
- **Certificates**: Generate certificates for course completions.
- **AI Recommendations**: Personalized course suggestions using AI.
- **Gamification**: Badges, streaks, and leaderboards to boost engagement.

## Monetization Extras

- **Coupons/Discounts**: Let instructors run promotions.
- **Affiliate Program**: Commission for users referring new students.
- **Enterprise Plans**: Bulk licenses for schools/companies.

## Setup & Installation

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [Yarn](https://yarnpkg.com/) (optional but recommended)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/e-learning-platform.git
   cd e-learning-platform
2. Install backend dependencies:
   ```bash
   cd server
   npm install
3.Install frontend dependencies:

  ```bash
  cd client
  npm install
4.Configure environment variables (e.g., MongoDB URI, PayPal credentials, JWT secret, etc.) in the .env file.

Start the application:

For the backend:
  ```bash
  cd server
  npm start
For the frontend:
  ```bash
  cd client
  npm run dev
The application will be accessible at http://localhost:3000.


