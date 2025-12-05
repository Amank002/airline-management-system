# Welcome to my Airline Management System


## How can I edit this code?

There are several ways of editing your application.
.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in VS Code.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <https://github.com/Amank002/airline-management-system>

# Step 2: Navigate to the project directory.
cd <airline-management-system>

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

## How can I deploy this project?

Simply open [Vercel](https://airline-management-system-gamma.vercel.app/) and click on Share -> Publish.

## Can I connect a custom domain to VS Code project?

Yes, you can!

What you can do is:

Host your VS Code project somewhere (GitHub Pages, Netlify, Vercel, traditional hosting, etc.).

Buy a domain (e.g., from Namecheap, GoDaddy, Google Domains…).

Point the domain’s DNS records to your hosting provider.

Tell the hosting provider to use that domain for your site.

Example with GitHub Pages (static website):

Push your project to GitHub.

In repo → Settings → Pages → choose branch (main), folder (/root or /docs) → Save.

In Pages → Custom domain add yourdomain.com.

At your domain registrar, create a CNAME record:

Name: www

Value: yourusername.github.io

(Optional) Add A records if you want root domain (yourdomain.com) to work too, following GitHub’s docs.

