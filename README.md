# Turf Plan B

This is the Plan B version of the Turf application, built with Next.js and Supabase.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Features

- Uses the same Supabase backend as the main Turf app
- Modern UI with Next.js and TypeScript
- Authentication and user management
- Real-time features
- Responsive design

## Environment Setup

Create a `.env.local` file with the following variables:

```env
# Application URLs
NEXT_PUBLIC_SITE_URL=your_site_url
NEXT_PUBLIC_API_URL=your_api_url

# Supabase Configuration
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_anon_key

# Feature Flags
NEXT_PUBLIC_ENABLE_SOCIAL_LOGIN=true
```

## Deploy on Vercel

The app is configured for deployment on Vercel. Check out the [deployment documentation](https://nextjs.org/docs/deployment) for more details.
