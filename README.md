# ShadCN + Next.js Boilerplate

This repository serves as a boilerplate for building modern web applications using [Next.js](https://nextjs.org/) and [ShadCN](https://shadcn.dev/), a customizable UI component library. It comes with a preconfigured setup for rapid development, best practices, and an easily customizable component library.

## Features

- **Next.js 13+**: The latest features, including App Router support, server-side rendering, and API routes.
- **ShadCN UI Components**: Pre-styled and accessible components based on Tailwind CSS, fully customizable to fit your project's needs.
- **Tailwind CSS**: A utility-first CSS framework for building custom user interfaces.
- **TypeScript**: Strict type checking with TypeScript for better developer experience.
- **ESLint & Prettier**: Linting and formatting configured for a consistent codebase.
- **Jest & React Testing Library**: Pre-configured for writing unit and integration tests.
- **GitHub Actions CI**: Automated testing and linting on every push.

## Getting Started

To use this boilerplate, you'll need to have [Node.js](https://nodejs.org/) installed. Follow these steps to get started:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies

```bash
yarn install
```

### 3. Run the Development Server

```bash
yarn dev
```

## Project Structure

```ruby
.
├── public/               # Static assets (images, icons, etc.)
├── src/
│   ├── components/       # ShadCN components and custom components
│   ├── pages/            # Next.js pages
│   ├── styles/           # Tailwind CSS and global styles
│   ├── utils/            # Utility functions and helpers
│   ├── hooks/            # Custom React hooks
│   ├── lib/              # External libraries or API clients
│   ├── types/            # TypeScript type definitions
│   └── tests/            # Unit and integration tests
├── .eslintrc.js          # ESLint configuration
├── jest.config.js        # Jest configuration
├── next.config.js        # Next.js configuration
├── tailwind.config.js    # Tailwind CSS configuration
└── tsconfig.json         # TypeScript configuration
```

## Customizing ShadCN Components

ShadCN components are built with Tailwind CSS, allowing for full customization. You can modify the components located in src/components/ to fit your design needs or create new ones using ShadCN as a starting point.

## Available Scripts

Start the development server.
```bash
yarn dev
```

Build the project for production.
```bash
yarn build
```

Run linting using ESLint.
```bash
yarn lint
```

Run tests using Jest.
```bash
yarn test
```

Format code using Prettier.
```bash
yarn format
```

## Testing

This boilerplate includes Jest and React Testing Library for testing your components and pages. To run tests, use:

```bash
yarn test
```

## Deployment

The boilerplate can be deployed to any platform that supports Next.js, such as Vercel, Netlify, or any cloud provider with a Node.js environment.

### Deploying to Vercel

#### Sign up for a Vercel account.
#### Install the Vercel CLI.
#### Run vercel in your project directory to deploy.

## Contributing
Feel free to contribute to this boilerplate by submitting issues or pull requests. Contributions are always welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

Next.js

ShadCN

Tailwind CSS

TypeScript
