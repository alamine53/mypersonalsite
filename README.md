# Ramzy Al-Amine - Personal Website

A minimal, one-page personal website built with HTML, CSS, and JavaScript.

## Features

- Dark mode toggle
- Responsive design
- Project grid with hover effects
- Publications list
- Clean, minimal aesthetic

## Deployment

This site is configured for deployment on Netlify.

### Deploy via Netlify

1. **Option 1: Deploy via Netlify UI**
   - Go to [Netlify](https://www.netlify.com/)
   - Sign up or log in
   - Click "Add new site" → "Import an existing project"
   - Connect your Git repository or drag and drop the project folder
   - Netlify will automatically detect the settings from `netlify.toml`

2. **Option 2: Deploy via Netlify CLI**
   ```bash
   # Install Netlify CLI
   npm install -g netlify-cli
   
   # Login to Netlify
   netlify login
   
   # Deploy
   netlify deploy --prod
   ```

3. **Option 3: Deploy via Git**
   - Push your code to GitHub, GitLab, or Bitbucket
   - Connect your repository to Netlify
   - Netlify will automatically deploy on every push

### Local Development

Simply open `index.html` in your browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## File Structure

```
.
├── index.html      # Main HTML file
├── netlify.toml    # Netlify configuration
├── .gitignore      # Git ignore file
└── README.md       # This file
```

## Customization

- Edit `index.html` to update content, styling, and functionality
- All styles are in the `<style>` tag within the HTML file
- Dark mode toggle is handled via JavaScript at the bottom of the file
