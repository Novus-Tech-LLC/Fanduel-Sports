# Contributing to Crypto Fantasy League

Thank you for your interest in contributing to Crypto Fantasy League! This document provides guidelines and instructions for contributing to the project.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## How to Contribute

### Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

- **Clear and descriptive title**
- **Steps to reproduce** the issue
- **Expected behavior** vs **actual behavior**
- **Screenshots** (if applicable)
- **Environment details** (OS, browser, Node.js version, etc.)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

- **Clear and descriptive title**
- **Detailed description** of the proposed enhancement
- **Use case** - why this enhancement would be useful
- **Possible implementation** (if you have ideas)

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** following our coding standards
3. **Test your changes** thoroughly
4. **Update documentation** if needed
5. **Commit your changes** with clear, descriptive commit messages
6. **Push to your fork** and submit a pull request

#### Pull Request Guidelines

- Keep PRs focused and small when possible
- Include a clear description of what the PR does
- Reference any related issues
- Ensure all tests pass (if applicable)
- Update documentation as needed
- Follow the existing code style

## Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/NovusTechLLC/Fanduel-Sports.git
   cd Fanduel-Sports
   ```

2. **Install dependencies**
   ```bash
   cd mini-app
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   # Edit .env.local with your configuration
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

## Coding Standards

### TypeScript

- Use TypeScript for all new code
- Provide explicit type annotations for function parameters and return types
- Avoid `any` types - use `unknown` or proper types instead
- Follow the existing code style and formatting

### React/Next.js

- Use functional components with hooks
- All component files should start with `"use client";` directive when needed
- Use existing shadcn/ui components when possible
- Follow Next.js 15 App Router conventions

### Code Style

- Use meaningful variable and function names
- Keep functions small and focused
- Add comments for complex logic
- Follow the existing indentation and formatting (2 spaces)

### Git Commit Messages

- Use clear, descriptive commit messages
- Start with a verb in imperative mood (e.g., "Add", "Fix", "Update")
- Reference issue numbers when applicable
- Example: `Fix: Resolve header layout issue on mobile devices (#123)`

## Project Structure

```
mini-app/
├── app/              # Next.js app directory
├── components/       # React components
│   ├── ui/          # shadcn/ui components
│   └── context/     # React context providers
├── lib/             # Utility functions and configs
└── public/          # Static assets
```

## Testing

- Test your changes in the development environment
- Test on different screen sizes (mobile, tablet, desktop)
- Test in Farcaster clients when possible
- Verify that existing functionality still works

## Documentation

- Update README.md if you add new features or change setup instructions
- Add JSDoc comments for new functions and components
- Update relevant documentation files in the `documentation/` directory

## Questions?

If you have questions about contributing, feel free to:

- Open an issue for discussion
- Contact the maintainers via the contact information in README.md

Thank you for contributing to Crypto Fantasy League! 🎉

