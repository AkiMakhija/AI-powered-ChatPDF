
<img width="1137" height="553" alt="4" src="https://github.com/user-attachments/assets/94c3b111-726c-421f-8173-3292e746a958" />

# Overview

Welcome to the "chatpdf-yt" project, a comprehensive chat application with PDF integration. This project is designed to provide a seamless chat experience where users can upload PDF files, create chats around them, and interact with an AI assistant. The AI assistant uses the OpenAI API to generate responses based on the chat context. The application also includes a subscription feature, where users can subscribe to access premium features. The subscription process is handled using Stripe for payments and webhooks for event processing.

# Upload PDF and Chat

<img width="1439" height="477" alt="chat area" src="https://github.com/user-attachments/assets/7b1a9f70-d68b-4a4a-b093-97541303f8dc" />

# Manage Subscription
<img width="1395" height="426" alt="5" src="https://github.com/user-attachments/assets/397e3373-d3d1-4a9d-989d-a772a4fecabf" />


# Technologies and Frameworks

- Next.js
- React
- TypeScript
- Tailwind CSS
- Clerk
- Drizzle ORM
- PostgreSQL
- AWS SDK
- OpenAI API
- Stripe
- Axios
- Pinecone
- Drizzle-kit
- OpenAI Edge
- Neon Database Serverless
- Drizzle-orm/neon-http
- @tanstack/react-query
- @clerk/nextjs
- clsx
- tailwind-merge

# Installation

Follow the steps below to install and setup the project:

1. **Clone the repository**

   Open your terminal and run the following command:

   ```bash
   git clone https://github.com/Elliott-Chong/chatpdf-yt.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd chatpdf-yt
   ```

3. **Install Node.js**

   The project requires Node.js version 13.4.19 or later. You can download it from [here](https://nodejs.org/en/download/).

4. **Install the required dependencies**

   Run the following command to install all the required dependencies:

   ```bash
   npm install
   ```

   This will install all the dependencies listed in the `package.json` file, including Next.js, React, React DOM, Axios, Stripe, Tailwind CSS, and other specific dependencies such as "@aws-sdk/client-s3" and "@clerk/nextjs".

5. **Setup environment variables**

    Create a `.env` file in the root directory of your project and add the required environment variables.

6. **Run the project**

    Now, you can run the project using the following command:

    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


