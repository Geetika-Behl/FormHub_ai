# 📌 FormHub-ai

Welcome to the **AI Form Builder** repository! This project leverages cutting-edge tools and frameworks to create a dynamic and efficient form-building platform powered by AI. The AI Form Builder provides a seamless drag-and-drop experience, empowering users to create forms effortlessly while collecting valuable insights.

---

## 🌟 Features

- **AI-Powered Form Creation**: Users can create forms by simply providing prompts, and the AI generates the necessary form fields based on the prompts.
- **Authentication**: Integrated with Next-auth for secure user sign-up, sign-in, and account management.
- **Responsive Design**: Powered by Shadcn UI for a responsive and visually appealing experience across devices.
- **Admin Dashboard**: Admin users can view all responses submitted to their forms.
- **Persistent Data Storage**: Secure data storage with PostgreSQL for form configurations, user details, and responses.
- **Type Safety**: Built with TypeScript for enhanced code maintainability.
- **Gemini AI API Integration**: Powers the AI form creation with robust AI capabilities.

---

## 🚀 Tools & Technologies

This project is built using:

- **Next.js 14**: Fast, SEO-friendly frontend framework.
- **Server Actions**: For seamless backend API integration.
- **Prisma ORM**: Efficient SQL ORM for database management.
- **TailwindCSS**: Rapid, responsive styling.
- **Neon PostgreSQL**: Scalable and reliable database solution.
- **Next-auth**: Open-source authentication solution for Next.js applications.
- **Shadcn UI**: A modern, customizable UI framework.
- **Gemini AI API**: For integrating artificial intelligence into applications.
- **PostgreSQL**: A powerful, open-source relational database system.
- **TypeScript**: A statically typed superset of JavaScript.

---

## Getting Started

### Development Server

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

### Environment Variables

Create a .env file in the root of your project and add the following:

```
KINDE_SITE_URL=<your-kinde-site-url>
KINDE_POST_LOGOUT_REDIRECT_URL=<your-post-logout-url>
KINDE_POST_LOGIN_REDIRECT_URL=<your-post-login-url>
NEXT_PUBLIC_APP_URL=<your-app-url>


DATABASE_URL=<pooler-database-url>
DIRECT_DATABASE_URL=<direct-database-url>

NEXT_PUBLIC_GEMINI_API_KEY=<gemini-api-key>

NEXT_PUBLIC_APP_URL="http://localhost:3000"
```

### Log in to Neon:

* Navigate to Neon and log in to your account.
* Access Project Settings:
  
      1  Select your project and go to the Settings tab.
  
      2. Find URLs:

           Direct Database URL: Under connection settings labeled "Direct Connection". Use this for DIRECT_DATABASE_URL.
           Pooler Database URL: Found under the "Connection Pooler" section. Use this for DATABASE_URL.

 
Note: For troubleshooting Neon database access, refer to the guide in _neon_database_help/database.md.

### Run the Application
Open ``` http://localhost:3000``` in your browser to view the app.

Start editing the page by modifying app/page.tsx. The page auto-updates as you make changes.

This project uses next/font to automatically optimize and load Geist, a new font family for Vercel.

### Learn More

To learn more about Next.js, check out:

Next.js Documentation - Learn about features and APIs.
Learn Next.js - An interactive tutorial.
Next.js GitHub Repository - Share your feedback and contributions.


### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the Vercel Platform by the creators of Next.js.

Check out the Next.js deployment documentation for more details.

### Preview

Form: Dynamic AI-powered form creation.
Dashboard: Admin interface for managing form responses.

### Overview

[Front Page][!https://github.com/Geetika-Behl/FormHub_ai/blob/main/src/frontpage.jpg]
[Video][!https://youtu.be/14CHpLY7Ur4]
