# Fullstack Trello Clone: Next.js 14, Server Actions, React, Prisma, Stripe, Tailwind, MySQL


![Screenshot](https://github.com/Conqxeror/trello-clone-e2e/assets/110852661/e43d0ff5-0c10-4379-92d1-59d004af14a2)


**Overview:**
Welcome to the Fullstack Trello Clone, a meticulously crafted project offering a comprehensive task management solution. Leveraging the power of Next.js 14, Server Actions, React, Prisma, Stripe, Tailwind, and MySQL, this project stands as a testament to modern web development practices.

**Key Features:**

1. **Authentication:**
   Secure and seamless user authentication ensures a personalized experience for every user.

2. **Organizations / Workspaces:**
   Efficiently organize your workflow by creating and managing distinct organizations or workspaces.

3. **Board Operations:**
   Empower users to create, rename, and delete boards, with the added aesthetic touch of random beautiful cover images from the Unsplash API.

4. **Activity Logging:**
   A comprehensive activity log keeps track of all actions within an organization, providing valuable insights into the workflow.

5. **List Management:**
   Create, rename, delete, and effortlessly reorder lists with intuitive drag & drop functionality.

6. **Card Operations:**
   Take control of your tasks with features like card creation, renaming, deletion, drag & drop reordering, and duplication.

7. **Board Limits and Subscriptions:**
   Set board limits for organizations and unlock the full potential with Stripe subscriptions, enabling unlimited boards.

8. **Landing Page:**
   A visually appealing landing page welcomes users and introduces them to the powerful capabilities of the application.

9. **Database and ORM:**
   The application is backed by a MySQL database managed through Prisma ORM, ensuring efficient and scalable data operations.

10. **UI Frameworks:**
    ShadcnUI and TailwindCSS collaborate to create a sleek and responsive user interface, enhancing the overall user experience.

**Prerequisites:**
Ensure Node.js version 18.x.x is installed on your system before diving into the setup process.

**Getting Started:**

1. **Clone the Repository:**
   ```
   git clone https://github.com/AntonioErdeljac/next13-trello.git
   ```

2. **Install Packages:**
   ```
   npm i
   ```

3. **Set Up Environment Variables:**
   Configure your environment variables, including Clerk, database, Unsplash, Stripe, and app-specific details.

4. **Prisma Setup:**
   ```
   npx prisma generate
   npx prisma db push
   ```

5. **Start the Application:**
   ```
   npm run dev
   ```
