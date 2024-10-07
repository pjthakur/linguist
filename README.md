<a name="readme-top"></a>

# Linguist - Interactive Language Learning Platform

Linguist is a platform designed to make language learning easy and engaging by incorporating gamified elements. It combines interactive language lessons with game-like features to create an immersive learning experience that motivates users to progress through fun and challenging activities.

<!-- Table of Contents -->
<details>
<summary>Table of Contents</summary>

- [Introduction](#introduction)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Deployment](#deployment)

</details>

## Introduction

Linguist transforms language learning into an interactive and enjoyable experience. By integrating gamified elements such as quests, challenges, and leaderboards, it keeps learners motivated and engaged. Users can track their progress, compete with others, and unlock achievements as they advance in their language skills.

## Tech Stack

- **React.js** - A JavaScript library for building user interfaces.
- **Next.js** - A React framework for server-rendered applications.
- **TypeScript** - A superset of JavaScript that adds static types.
- **Tailwind CSS** - A utility-first CSS framework for designing custom UIs.
- **PostgreSQL** - A powerful, open-source relational database.
- **Stripe** - A payment processing platform for managing transactions.
- **Clerk** - Authentication and user management system.
- **Vercel** - Hosting platform for deploying Next.js applications.

## Getting Started

1. **Install Dependencies**:
   - Ensure **Git** and **Node.js** are installed.
   - Clone the repository:

     ```bash
     git clone <repository-url>
     ```

   - Navigate to the project directory:

     ```bash
     cd Linguist
     ```

   - Install project dependencies:

     ```bash
     npm install --legacy-peer-deps
     ```

2. **Configuration**:
   - Create a `.env` file in the root directory.
   - Copy the contents from `.env.example` to `.env` and configure the necessary keys and credentials:

     - Clerk Authentication Keys
     - Neon Database URI
     - Stripe API Key and Webhook Secret
     - Public App URL
     - Clerk Admin User IDs

3. **Seed Database**:
   - Run the seed script to populate the database:

     ```bash
     npm run db:prod
     ```

4. **Start Development Server**:
   - Run the development server:

     ```bash
     npm run dev
     ```

## Deployment

To deploy the application, use the [Vercel Platform](https://vercel.com) for a streamlined deployment process. For more details, refer to the [Next.js deployment documentation](https://nextjs.org/docs/deployment).

<br />
<p align="right">(<a href="#readme-top">back to top</a>)</p>
#
