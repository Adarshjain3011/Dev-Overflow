
# Dev-Overflow

Dev-Overflow is a dynamic web application designed for developers to share knowledge, connect with peers, and explore job opportunities. The platform leverages cutting-edge technologies to provide a seamless and efficient user experience.

## Features

- **Knowledge Sharing**: Post and discover insightful content from the developer community.
- **AI-Powered Suggestions**: Integrated OpenAI to offer intelligent code suggestions and content generation.
- **Job Board**: Search and post job opportunities specifically for developers.
- **User Authentication**: Secure login and registration using Clerk.
- **Responsive Design**: Styled with Tailwind CSS for a consistent and mobile-friendly interface.
- **Scalable Backend**: Data management with MongoDB for reliability and scalability.

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Next.js API Routes
- **Authentication**: Clerk
- **Database**: MongoDB
- **AI Integration**: OpenAI API

Install dependencies:
npm install

## Installation
Set up environment variables:
Create a .env.local file in the root directory and add your environment variables.

NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_frontend_api_key
CLERK_API_KEY=your_clerk_api_key
MONGODB_URI=your_mongodb_uri
OPENAI_API_KEY=your_openai_api_key

Run the development server:
npm run dev 


1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/dev-overflow.git
   cd dev-overflow
