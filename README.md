# Financial Dashboard Project

This project is a full-stack Next.js application that creates a financial dashboard. It includes a public home page, a login page, and authenticated dashboard pages where users can manage invoices. This course is designed to provide the essential skills needed to build complete Next.js applications.

-----

## Features

This project will guide you through implementing the following features:

  * **Styling**: Learn various methods for styling your application in Next.js.
  * **Optimizations**: Discover how to optimize images, links, and fonts for better performance.
  * **Routing**: Master creating nested layouts and pages using the file-system routing feature of Next.js.
  * **Data Fetching**: Understand how to set up a Postgres database on Vercel and learn best practices for fetching and streaming data.
  * **Search and Pagination**: Implement search and pagination functionalities using URL search parameters.
  * **Mutating Data**: Learn how to modify data using React Server Actions and revalidate the Next.js cache.
  * **Error Handling**: Handle general application errors and 404 not found errors gracefully.
  * **Form Validation and Accessibility**: Implement server-side form validation and get tips for improving accessibility.
  * **Authentication**: Add authentication to your application using NextAuth.js and Middleware.
  * **Metadata**: Learn how to add metadata to your pages for better SEO and social sharing.

-----

## Prerequisite Knowledge

This course assumes you have a foundational understanding of **React** and **JavaScript**. If you are new to React, it is recommended to complete a foundational course covering components, props, state, hooks, Server Components, and Suspense before starting this project.

-----

## System Requirements

Before you begin, please ensure your system meets the following requirements:

  * **Node.js**: Version 18.17.0 or later installed on your machine.
  * **Operating System**: Compatible with MacOS, Windows (including WSL), or Linux.

-----

## Steps to Run This Project

To get the project up and running on your local machine, follow these steps:

1.  **Clone the Repository**:
    Open your terminal and clone the project repository to your local machine using the following command:

    ```bash
    git clone https://github.com/Prayoga-bit/AcmeNext.git
    ```

2.  **Navigate to the Project Directory**:
    Change your current directory to the newly cloned project folder:

    ```bash
    cd AcmeNext
    ```

3.  **Install Dependencies**:
    Install all the necessary project dependencies using npm (or your preferred package manager like yarn or pnpm):

    ```bash
    pnpm install
    #or
    npm install
    #or
    yarn
    ```

4.  **Set Up Environment Variables**:
    Create a `.env.local` file in the root of your project directory. This file will hold your environment-specific variables, such as database connection strings and authentication secrets. You can typically copy the `.env.example` file if one is provided.

    ```bash
    cp .env.example .env.local
    ```

    Now, open the `.env.local` file and fill in the required values.

5.  **Run the Development Server**:
    Start the Next.js development server to view the application in your browser:

    ```bash
    npm run dev
    #or
    pnpm dev
    #or
    yarn dev
    ```

6.  **View the Application**:
    Open your web browser and navigate to the following address to see the application live:
    [http://localhost:3000](https://www.google.com/search?q=http://localhost:3000)