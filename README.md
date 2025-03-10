# Gold Coast Arms Website

A modern e-commerce website for Gold Coast Arms, built with Next.js, TypeScript, and Tailwind CSS.

## Features

- Modern, responsive design
- Product catalog with filtering and sorting
- Shopping cart functionality with persistent storage
- Secure checkout process
- Brand showcase
- User authentication (coming soon)
- Admin dashboard (coming soon)

## Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **State Management:** Zustand
- **Database:** PostgreSQL with Prisma (coming soon)
- **Payment Processing:** Stripe (coming soon)
- **Authentication:** NextAuth.js (coming soon)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/Mkisil7/Gold-Coast-Arms.git
cd Gold-Coast-Arms
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your environment variables:
```env
DATABASE_URL="your_database_url"
STRIPE_PUBLIC_KEY="your_stripe_public_key"
STRIPE_SECRET_KEY="your_stripe_secret_key"
NEXTAUTH_SECRET="your_nextauth_secret"
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
gold-coast-arms/
├── src/
│   ├── app/              # Next.js app directory
│   ├── components/       # React components
│   ├── lib/             # Utility functions and store
│   └── utils/           # Helper functions
├── public/              # Static assets
│   └── images/          # Image assets
├── prisma/             # Database schema and migrations
└── package.json        # Project dependencies
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Repository

- **GitHub:** [https://github.com/Mkisil7/Gold-Coast-Arms](https://github.com/Mkisil7/Gold-Coast-Arms)
- **SSH:** `git@github.com:Mkisil7/Gold-Coast-Arms.git`
