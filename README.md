# From 231 Newsletter Website

This is the static website for the "From 231" newsletter, covering Vancouver Whitecaps FC. Built with Jekyll and the Just The Docs theme, hosted on GitHub Pages.

## Quick Setup

### Prerequisites
- A GitHub account
- Basic familiarity with Git (or GitHub Desktop)

### Installation Steps

1. **Create a new GitHub repository**
   - Go to GitHub.com and create a new repository
   - Name it something like `from231-site` or `newsletter-site`
   - Make it public
   - Don't initialize with README (you're adding your own files)

2. **Create the folder structure and add files**
   - Follow the instructions in the "File Structure" section below
   - Copy and paste each file's content from the artifacts

3. **Upload your logo**
   - Create the path: `assets/images/`
   - Upload `from231-logo.png` to this location

4. **Enable GitHub Pages**
   - Go to your repository Settings
   - Click "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

5. **Update configuration**
   - Edit `_config.yml`
   - Change the `url` line to match your GitHub Pages URL:
```yaml
     url: "https://YOUR-USERNAME.github.io"
```
   - If using a custom repository name, also update `baseurl`:
```yaml
     baseurl: "/YOUR-REPO-NAME"
```

6. **Wait for deployment**
   - GitHub Pages typically takes 1-3 minutes to build and deploy
   - Check the "Actions" tab to see deployment progress
   - Once complete, visit your site at the URL shown in Settings > Pages

## File Structure
