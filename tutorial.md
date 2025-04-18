🧠 Zero to One: Beginner Software Project Tutorial

Welcome! This is a step-by-step guide to help you go from zero knowledge to having your own online project, hosted on the internet. It's split into two parts:

⏱ 1 Hour Portfolio Version — Build a simple online markdown page.

🛠 6 Hour Web App Version — Build and deploy a simple web app.

⏱ 1-Hour Version (Build a Portfolio Markdown Page)

1. Create a GitHub Account

Go to https://github.com/

Sign up for a free account.

2. Create a Git Repository

Click "New" or go to https://github.com/new

Choose a name like my-first-site

Check "Public" and click Create repository

3. Pull the Repo Locally

Install Git (if you don’t have it): https://git-scm.com/

# Open Terminal or Command Prompt:
git clone https://github.com/YOUR-USERNAME/my-first-site.git
cd my-first-site

4. Open in VSCode or Cursor

Download VSCode or Cursor

Open the cloned folder from File > Open Folder

5. Create and Edit a Markdown File

Inside your repo, create a file called index.md

# Hello World 👋

This is my first page on the internet!

Save the file

6. Upload to GitHub Pages

Commit and push the file:

git add index.md
git commit -m "add index file"
git push

7. Set Up GitHub Pages

Go to your repo > Settings > Pages

Under "Source", select main branch, and root folder (or /docs if needed)

GitHub will generate a link like:

https://your-username.github.io/my-first-site/

Done ✅

🛠 6-Hour Version (Build & Deploy a Web App)

1. Draw Your UI with Excalidraw

Go to https://excalidraw.com

Sketch the layout: header, buttons, login form, etc.

2. Use a Next.js Template

Use the official template:

npx create-next-app@latest my-web-app
cd my-web-app
npm run dev

3. Use AI Tools to Build Features

Ask ChatGPT/Claude to build components

Copy/paste the output into your code

Example:

"Write a Next.js component for a login page using TailwindCSS."

4. Add ShadCN UI Design

Follow: https://ui.shadcn.dev/docs/installation

npx shadcn-ui@latest init

Use components like <Button />, <Card />, etc.

5. Add a .env File

Create a .env.local file:

NEXT_PUBLIC_API_URL=https://your-api.com

6. (Optional) Add Supabase for Auth

Sign up at https://supabase.com

Create a new project and copy the URL + anon key

Install client:

npm install @supabase/supabase-js

Create a login page using Supabase Auth

7. Push to Vercel

Go to https://vercel.com

Connect your GitHub repo

Deploy project

8. Buy a Domain from DNSimple

Go to https://dnsimple.com

Buy a short, easy domain

9. Set Custom Domain on Vercel

Go to your project in Vercel

Settings > Domains > Add Domain

Follow the steps to connect your DNSimple domain

🎉 Live! You now have your own fullstack app on your own domain.

👋 Final Notes

You did it. From zero to your first working app.

Don’t stop here. Keep iterating.

Break things, fix them, learn more.

This tutorial is hosted at https://your-username.github.io

Happy hacking 💻