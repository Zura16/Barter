# Barter

Barter is a web application designed to facilitate trading and exchanging goods and services. Built using React, Vite, TypeScript, and Tailwind CSS, the platform integrates with Appwrite Cloud for authentication, database storage, and file management. Users can share items they want to trade, specify the item's condition, define what they want in exchange, estimate its value, track the trade status, and propose trade offers to other users.

## Features

* User Authentication: Secure sign-up, sign-in, and sign-out powered by Appwrite.
* Profile Management: Users can update their avatar, name, username, and bio.
* Post Creation and Editing: Users can upload photos, add locations, list tags, and define specific barter details including Item Condition, Trade Status, Looking-For requirements, and Estimated Value.
* Interactive Trade Proposals: Viewers can click a button on listings to open an interactive trade proposal form to offer their own items or skills in exchange.
* Responsive Interface: Tailwind CSS layouts optimized for desktop, tablet, and mobile views.
* Data Querying: Fast queries, caching, and state management using TanStack React Query.

## Tech Stack

* Frontend Library: React 18
* Build Tool: Vite
* Programming Language: TypeScript
* Styling: Tailwind CSS
* Backend-as-a-Service: Appwrite Cloud
* Form Handling: React Hook Form
* Schema Validation: Zod
* State Management: TanStack React Query (React Query)

## Getting Started

### Prerequisites

Make sure you have Node.js installed on your computer.

### Installation

1. Clone the repository to your local machine.
2. Open your terminal in the project directory.
3. Install the dependencies:
   ```bash
   npm install
   ```

### Environment Setup

Create a `.env.local` file in the root of the project with your Appwrite Cloud configuration:
```env
VITE_APPWRITE_URL=https://cloud.appwrite.io/v1
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_STORAGE_ID=your_storage_id
VITE_APPWRITE_USER_COLLECTION_ID=your_user_collection_id
VITE_APPWRITE_POST_COLLECTION_ID=your_post_collection_id
VITE_APPWRITE_SAVES_COLLECTION_ID=your_saves_collection_id
```

### Running Locally

To start the development server:
```bash
npm run dev
```
The application will be accessible at http://localhost:5173 (or another port shown in your terminal).

### Production Build

To compile and build the production bundle:
```bash
npm run build
```
The compiled build output will be located in the `dist` directory.
