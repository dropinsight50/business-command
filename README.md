# Advanced Business Task Manager

This project is a static web application for advanced business task management. The main file is `index.html`, originally exported as an MHTML archive, and is ready to be hosted as a static site.

## How to Use

1. Clone this repository from GitHub.
2. The main page is `index.html`.
3. You can view it locally by opening `index.html` in your browser.

## Deploying to Netlify

1. Push this repository to GitHub.
2. Connect your GitHub repository to Netlify.
3. Set the publish directory to the root (`/`).
4. Netlify will automatically serve `index.html` as the homepage.

## Notes
- No build step is required; this is a static site.
- You can add more static assets (images, CSS, JS) as needed. 

---

## Deployment

### GitHub
1. Initialize a git repository:
   ```sh
git init
git add .
git commit -m "Initial commit"
   ```
2. Create a new repository on GitHub and follow the instructions to push your code.

### Netlify
1. [Sign up](https://app.netlify.com/signup) or log in to Netlify.
2. Click "Add new site" > "Import an existing project".
3. Connect your GitHub repository.
4. Set the build command to `N/A` (or leave blank) and the publish directory to `.` (the root).
5. Deploy the site.

Your site will be live on a Netlify URL. You can set up a custom domain in Netlify settings. 