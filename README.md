# AI Career Coach - SensAi

This project is a full-stack AI career coach application, "Sensei," built using Next.js, Shadcn UI, and various other modern technologies. It provides users with AI-powered career guidance and support.


### 📌 Live Demo  
[🚀 Click here to view the deployed project](https://sensai-brown.vercel.app/)  

## Features

* **AI-Driven Career Advice:** Leverage the power of AI to get personalized career recommendations.
* **Modern UI:** Built with Shadcn UI for a sleek and responsive user interface.
* **Full-Stack Development:** Utilizes Next.js for both frontend and backend development.
* **Database Integration:** Uses Neon DB and Prisma for efficient data management.
* **Styled with Tailwind CSS:** Ensures a consistent and customizable design.
* **Background Jobs:** Implements background job processing with Inngest.

## Technologies Used

* **Next.js:** React framework for building server-rendered applications.
* **Shadcn UI:** Reusable components built with Radix UI and Tailwind CSS.
* **Tailwind CSS:** Utility-first CSS framework.
* **Prisma:** Next-generation ORM.
* **Neon DB:** Serverless PostgreSQL database.
* **Inngest:** Background job and workflow system.

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/AkshayTiwari27/SensAi.git
    cd ai-career-coach
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Set up environment variables:**

    * Create a `.env` file in the root directory.
    * Add the following environment variables, replacing the placeholders with your actual values:

        ```
        DATABASE_URL=your_neon_db_url
        
        NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_public_key
        CLERK_SECRET_KEY=your_clerk_secret_key
        
        NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
        NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
        NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
        NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
        
        GEMINI_API_KEY=your_gemini_api_key


        ```

4.  **Run database migrations:**

    ```bash
    npx prisma migrate dev
    ```

5.  **Start the development server:**

    ```bash
    npm run dev
    ```

6.  **Open your browser and navigate to `http://localhost:3000`.**


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

* Thanks to the creators of Next.js, Shadcn UI, Tailwind CSS, Prisma, Neon DB, and Inngest.

