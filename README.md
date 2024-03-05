# Fullstack Trello Clone: Next.js 14

This is a Fullstack Trello Clone built with Next.js 14, featuring Server Actions, React, Prisma, Stripe, Tailwind, MySQL, and more...

## Key Features

- **Authentication**: Secure user authentication.
- **Organizations / Workspaces**: Organize your boards into workspaces.
- **Board Management**: Create, rename, and delete boards.
- **Beautiful Covers**: Utilizes Unsplash API for random cover images.
- **Activity Log**: Keep track of activities within your organization.
- **List Operations**: Create, rename, delete, reorder, and copy lists.
- **Card Operations**: Create, rename, delete, reorder, and copy cards.
- **Card Activity Log**: Track changes and activities related to cards.
- **Board Limit**: Set limits for boards within each organization.
- **Stripe Subscription**: Enable subscription to unlock unlimited boards.
- **Landing Page**: Attractive landing page for your application.
- **MySQL Database**: Persistent storage using MySQL.
- **Prisma ORM**: Modern database access with Prisma.
- **UI Libraries**: Utilizes ShadCn UI & TailwindCSS for a sleek user interface.

## Prerequisites

- Node.js version 18.x.x

## Getting Started

1. **Clone the repository**:

   ```shell
   git clone https://github.com/bricecoding/next14-trello.git
   ```

2. **Install packages**:

   ```shell
   npm install
   ```

3. **Setup .env file**:

   Add your environment variables to the `.env` file:

   ```shell
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   # ... (add other variables)
   ```

4. **Setup Prisma**:

   Add Postgresql or MySql Database (I used Neon):

   ```shell
   npx prisma generate
   npx prisma db push
   ```

5. **Start the app**:

   ```shell
   npm run dev
   ```

## Available Commands

Running commands with npm:

| Command | Description                               |
| ------- | ----------------------------------------- |
| `dev`   | Starts a development instance of the app. |
