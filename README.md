# CraveCompass Website

A simple two-page static website for CraveCompass.

## Pages

1. **index.html** - About page with app information and contact details
2. **privacy.html** - Privacy policy page (accessible at /privacy)

## Files

- `index.html` - Home/About page
- `privacy.html` - Privacy policy page
- `style.css` - Shared stylesheet for both pages
- `README.md` - This file

## How to View Locally

Simply open `index.html` in your web browser:
```bash
open index.html
```

Or use a simple HTTP server:
```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit: `http://localhost:8000`

## Deployment Options

This is a static website that can be deployed anywhere:

### Option 1: GitHub Pages (Free)
1. Create a new GitHub repository
2. Push these files to the repository
3. Go to Settings > Pages
4. Select the branch and save
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 2: Netlify (Free)
1. Sign up at netlify.com
2. Drag and drop the `newfolder` directory
3. Your site will be live instantly with a custom URL

### Option 3: Vercel (Free)
1. Sign up at vercel.com
2. Import your GitHub repository or drag and drop
3. Deploy instantly

### Option 4: Firebase Hosting
```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```

## Customization

### Update Contact Information
Edit the email addresses in both `index.html` and `privacy.html`:
- `support@cravecompass.app`
- `hello@cravecompass.app`

### Update App Store Links
In `index.html`, replace the `#` placeholders with actual App Store and Google Play URLs.

### Modify Colors
The main brand color is `#e74c3c` (red). To change it, search and replace in `style.css`.

## Notes

- Fully responsive (mobile-friendly)
- No JavaScript required
- No build process needed
- Works on any web server
- Clean, modern design
