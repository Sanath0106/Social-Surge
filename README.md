# Magic Social - AI Content Generator

Magic Social is a powerful, AI-driven web application that helps you generate high-quality social media content in seconds. Whether you need a catchy YouTube video description, trending Instagram hashtags, or a professional LinkedIn post, Magic Social has you covered.

## ✨ Features

- **AI-Powered Content Generation**: Leverage the power of Gemini AI to create engaging and relevant content for your social media platforms.
- **Multiple Content Templates**: Choose from a variety of content templates, including:
  - YouTube Video Descriptions
  - YouTube Video Ideas
  - Instagram Hashtags
  - TikTok Hashtags
  - LinkedIn Posts
  - Tweets
- **User-Friendly Interface**: A clean and intuitive interface that makes content generation a breeze.
- **Secure Authentication**: User authentication is handled by Clerk, ensuring that your data is safe and secure.
- **Subscription-Based Credits**: Users can purchase credits through Stripe to generate content.

## 🚀 Technologies Used

- **Framework**: [Next.js](https://nextjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Authentication**: [Clerk](https://clerk.com/)
- **Database**: [PostgreSQL](https://www.postgresql.org/)
- **ORM**: [Prisma](https://www.prisma.io/)
- **AI**: [Gemini AI](https://deepmind.google/technologies/gemini/)
- **Payments**: [Stripe](https://stripe.com/)

## 🏁 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- PostgreSQL

### Installation

1. **Clone the repo**
   ```sh
   git clone https://github.com/your-username/magic-social.git
   ```
2. **Install NPM packages**
   ```sh
   npm install
   ```
3. **Set up environment variables**
   - Create a `.env` file in the root of your project and add the following environment variables:
     ```env
     DATABASE_URL="your-database-url"
     NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your-clerk-publishable-key"
     CLERK_SECRET_KEY="your-clerk-secret-key"
     STRIPE_SECRET_KEY="your-stripe-secret-key"
     GEMINI_API_KEY="your-gemini-api-key"
     ```
4. **Set up the database**
   - Run the following command to apply the database schema:
     ```sh
     npx prisma db push
     ```
5. **Run the development server**
   ```sh
   npm run dev
   ```
   - Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
