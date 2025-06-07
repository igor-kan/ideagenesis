# ideagenesis

A web application for exploring and generating ideas. (Please update this description!)

## Project info

## How can I edit this code?

There are several ways of editing your application.

### Edit locally

If you want to work locally using your own IDE, you can clone this repo and push changes.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone https://github.com/igor-kan/ideagenesis.git

# Step 2: Navigate to the project directory.
cd ideagenesis

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## Live Demo

Visit the live site: [https://igor-kan.github.io/ideagenesis](https://igor-kan.github.io/ideagenesis)

## Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions whenever changes are pushed to the `main` branch.

The static site is built from the `main` branch and served on GitHub Pages.

## Can I connect a custom domain to my project?

Yes, you can! Refer to your hosting provider's documentation for instructions.

## Deployment

To deploy your application, you can use a platform like Vercel, Netlify, or your own server.

For Vercel or Netlify, you typically connect your Git repository and configure the build settings. The platform will then automatically build and deploy your application whenever you push changes to the connected branch.

If deploying to your own server, you will need to build the application and then copy the build artifacts to your server.

```bash
npm run build
```

This command will create a `dist` folder (or similar, depending on your build configuration) with the optimized, static assets for your application.
