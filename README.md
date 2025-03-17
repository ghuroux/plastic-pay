# Plastic Pay - Delivery Management System

A modern web application for managing plastic recycling deliveries and payments. Built with Next.js, Express.js, and Supabase.

## Features

- User authentication and authorization with role-based access control
- Client management system
- Delivery tracking and management
- Payment processing integration
- Real-time updates and notifications
- Responsive design for all devices
- Email notifications via SendGrid

## Tech Stack

- **Frontend:**
  - Next.js 14 with App Router
  - TypeScript
  - Tailwind CSS
  - React Hook Form
  - Zod for validation
  - Headless UI components

- **Backend:**
  - Next.js API Routes
  - Express.js middleware
  - TypeScript

- **Database & Auth:**
  - Supabase (PostgreSQL)
  - Supabase Auth

- **Email:**
  - SendGrid

- **Deployment:**
  - Vercel

## Prerequisites

- Node.js 18.x or later
- npm or yarn
- Supabase account
- SendGrid account
- Payment system API access

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/plastic-pay.git
   cd plastic-pay
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Copy the environment variables file and fill in your values:
   ```bash
   cp .env.example .env.local
   ```

4. Set up your environment variables in `.env.local`:
   ```
   NEXT_PUBLIC_SUPABASE_URL=your-supabase-project-url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
   SUPABASE_SERVICE_ROLE_KEY=your-supabase-service-role-key
   SENDGRID_API_KEY=your-sendgrid-api-key
   SENDGRID_FROM_EMAIL=your-verified-sender-email
   ```

5. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Database Setup

1. Create a new Supabase project
2. Run the migration scripts in `supabase/migrations/`
3. Set up the necessary policies for row-level security

## Development

### Directory Structure

- `/src/app` - Next.js pages and API routes
- `/src/components` - Reusable React components
- `/src/context` - React context providers
- `/src/hooks` - Custom React hooks
- `/src/lib` - Utility functions and API clients
- `/src/types` - TypeScript type definitions
- `/public` - Static assets

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build production bundle
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run test` - Run tests

## Deployment

The application is configured for deployment on Vercel:

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Configure environment variables in Vercel
4. Deploy!

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, email support@plasticpay.com or open an issue in the GitHub repository.
