# Storage Management Solution

A web-based application for storage management, built with modern technologies like **React**, **TypeScript**, **Appwrite**, and **Tailwind CSS**. This application provides an easy-to-use interface for managing files, performing CRUD operations, and using integrated features like authentication, file uploads, and data storage.

## Features

- **Authentication**: Secure sign-up, login, and user management using Appwrite's authentication service.
- **File Management**: Upload, store, and manage files with various types supported.
- **Responsive UI**: A clean, responsive user interface designed using Tailwind CSS for optimal experience across devices.
- **Theming**: Customizable themes for a personalized user experience.
- **Real-time Updates**: Instant updates when new files are added or modified.

## Technologies Used

- **Frontend**: 
  - React
  - TypeScript
  - Tailwind CSS
  - Next.js

- **Backend**: 
  - Appwrite (for database, authentication, and file storage)

- **Database**: 
  - Appwrite Database (No separate MongoDB integration used)

- **Deployment**: 
  - Vercel (for frontend hosting)
  - Appwrite (for backend services)

## Installation

### Prerequisites

- Node.js (v14 or higher)
- Appwrite instance running (either locally or using Appwrite Cloud)

### Clone the Repository

```bash
git clone https://github.com/Ujjwal-270/storage_management_solution.git
cd storage_management_solution
```

### Install Dependencies

-npm install

### Setup Environment Variables
Create a .env.local file in the root of the project and add your Appwrite project details:

-NEXT_PUBLIC_APPWRITE_ENDPOINT=<your-appwrite-endpoint>
-NEXT_PUBLIC_APPWRITE_PROJECT_ID=<your-appwrite-project-id>
-NEXT_PUBLIC_APPWRITE_DATABASE_ID=<your-appwrite-database-id>

## Deployment

### Deploy to Vercel

1. If you haven't already, create an account on [Vercel](https://vercel.com/).
2. After logging in, click on **New Project**.
3. Select your GitHub repository and follow the prompts.
4. Vercel will automatically detect that this is a Next.js app and configure the deployment for you.
5. Once the deployment process is complete, Vercel will provide a live URL where your application is hosted.

### Configure Appwrite in Production

Once your application is deployed to Vercel, you need to configure your Appwrite instance for production:

- Ensure your Appwrite endpoint is publicly accessible.
- Update the environment variables in Vercel:
  - `NEXT_PUBLIC_APPWRITE_ENDPOINT=<your-appwrite-public-endpoint>`
  - `NEXT_PUBLIC_APPWRITE_PROJECT_ID=<your-appwrite-project-id>`
  - `NEXT_PUBLIC_APPWRITE_DATABASE_ID=<your-appwrite-database-id>`

To update the environment variables in Vercel:

1. Go to your project in the Vercel dashboard.
2. Navigate to **Settings** → **Environment Variables**.
3. Add the required environment variables (`NEXT_PUBLIC_APPWRITE_ENDPOINT`, `NEXT_PUBLIC_APPWRITE_PROJECT_ID`, and `NEXT_PUBLIC_APPWRITE_DATABASE_ID`).
4. Click **Save** and redeploy the project to apply the changes.

After deploying, your application should be accessible on the Vercel URL, with all functionality tied to the live Appwrite backend.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Appwrite**: Provides backend services like authentication, database management, and file storage.
- **Tailwind CSS**: Enables responsive design and rapid UI development.
- **React**: The JavaScript library used for building the user interface.
- **Next.js**: A React framework that simplifies server-side rendering and static site generation.

## Contact

For any questions, suggestions, or feedback, feel free to reach out to me.
