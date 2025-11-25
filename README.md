# Spottaa

Spottaa is a modern event discovery and management platform that allows users to discover, create, and attend amazing events. Whether you’re hosting or attending, Spottaa makes every event memorable. Join our community and explore a variety of events tailored to your interests.

## Features

- Discover events in your area or online
- Create and manage your own events easily
- User authentication and account management powered by Clerk
- Interactive event exploration and registration
- QR code scanning for event check-ins
- Responsive and beautiful UI built with Radix UI and TailwindCSS

## Getting Started

### Prerequisites

- Node.js (version 16 or higher recommended)
- npm (comes with Node.js)
- A Convex backend account for serverless backend hosting (https://docs.convex.dev/quickstart/nextjs)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/ritikdevelop/spottaa.git
cd spottaa
```

2. Install dependencies:

```bash
npm install
```

### Environment Variables

Create a file named `.env.local` in the root of the project with the environment variables as shown below. Replace the placeholder values with your actual configuration:

```env
NEXT_PUBLIC_CONVEX_URL=https://your-convex-app.convex.cloud
CLERK_FRONTEND_API=your-clerk-frontend-api
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=http://localhost:3000/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=http://localhost:3000/sign-up
```

### Running the Development Server

Start the Next.js development server:

```bash
npm run dev
```

Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to see Spottaa in action.

### Building for Production

To build the application for production:

```bash
npm run build
```

To start the production server after building:

```bash
npm start
```

## Project Structure

- `app/` - Next.js app directory containing pages, layouts, and components organized by route groups.
- `components/` - Reusable UI components and widgets.
- `convex/` - Serverless backend functions and schema implemented with Convex.
- `hooks/` - Custom React hooks for business logic and state management.
- `lib/` - Utility functions and helpers.
- `public/` - Static assets like images and icons.
- `styles/` - Global and component-specific styles (mostly TailwindCSS).
- Configuration files like `next.config.mjs`, `tailwind.config.js`, and ESLint configs for development environment setup.

## Technologies Used

- [Next.js](https://nextjs.org/) - React framework for server-side rendering and static site generation.
- [React](https://reactjs.org/) - JavaScript library for building user interfaces.
- [Convex](https://convex.dev/) - Backend as a service for real-time data.
- [Clerk](https://clerk.dev/) - User authentication and management.
- [TailwindCSS](https://tailwindcss.com/) - Utility-first CSS framework.
- [Radix UI](https://radix-ui.com/) - Accessible React UI components.
- [React Hook Form](https://react-hook-form.com/) - Form validation and management.

## Contribution

Contributions are welcome! Feel free to submit issues, open pull requests, or suggest improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


---

Feel free to explore and enhance Spottaa to fit your event discovery needs!
