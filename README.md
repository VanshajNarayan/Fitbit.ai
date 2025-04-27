<h1 align="center">💪 Your personal AI-powered fitness companion! 🤖</h1>


   ![image alt](/public/poster.png)

   <br>
    
  <h3 align="center">Home Page</h3> <br>
  
   ![image alt](/public/fitbit-ai.png)

   
  <h3 align="center">Generate-program Page</h3> <br>
  
   ![image alt](/public/generate_program.png)

   
  <h3 align="center">Profile Page</h3> <br>
  
   ![image alt](/public/profile_page.png)


   <br>

   ## ✨ Highlights

- 🚀 **Tech Stack**: Next.js, React, Tailwind & Shadcn UI
- 🎙️ **Voice AI Assistant**: Vapi
- 🧠 **LLM Integration**: Gemini AI
- 🏋️ **Personalized Workout Plans**
- 🥗 **Custom Diet Programs**
- 🔒 **Authentication & Authorization**: Clerk
- 💾 **Database**: Convex
- 🎬 **Real-time Program Generation**
- 💻 **Layouts**
- 🎭 **Client & Server Components**

<br>

## 🚀 Features

- 🤖 **Smart AI Assistant**: Engage in conversation with an AI that asks about your fitness goals, physical condition, and preferences
- 🏋️ **Personalized Workout Plans**: Get custom exercise routines based on your fitness level, injuries, and goals
- 🥗 **Diet Recommendations**: Receive personalized meal plans accounting for your allergies and dietary preferences
- 🔐 **User Authentication**: Sign in with GitHub, Google, or email/password
- 📋 **Program Management**: Create and view multiple fitness programs with only the latest one active
- 📱 **Responsive Design**: Beautiful UI that works across all devices


<br>

## 🛠️ Tech Stack

- Next.js 14
- React 19
- Tailwind CSS
- Shadcn UI
- Clerk Authentication
- Convex Database
- Vapi Voice AI
- Gemini AI (LLM Integration)

<br>

📦 Getting Started
Follow these steps to get the project up and running locally:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies:

bash
Copy
Edit
npm install
# or
yarn install
Set up your environment variables as shown above.

Run the development server:

bash
Copy
Edit
npm run dev
# or
yarn dev
Open http://localhost:3000 in your browser to see the app.

<br>
🌐 Deployment
This application can be easily deployed to Vercel:

Build the application:

bash
Copy
Edit
npm run build
# or
yarn build
Start the production server:

bash
Copy
Edit
npm run start
# or
yarn start
Or connect your GitHub repository to Vercel for automatic deployments.

<br>
🖥️ Technologies Used
Next.js: React framework for building the frontend and API routes

Tailwind CSS & Shadcn UI: For styling and UI components

Clerk: Authentication and user management

Vapi: Voice agent platform for conversational AI

Convex: Real-time database

Gemini AI: Large Language Model for generating personalized fitness programs

<br>
📚 Learn More
To learn more about the technologies used in this project, check out the official documentation:

Next.js Documentation

Clerk Documentation

Vapi Documentation

Convex Documentation

Gemini AI Documentation

<br>


## 🔑 Environment Variables

Make sure to set the following environment variables before running the project:

```bash
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
