# Allwin Groups Website

A simple, professional static website for Allwin Groups, hosted on GitHub Pages.

## Features

- 📱 Fully responsive design
- 🎨 Modern and clean UI
- ⚡ Fast loading
- 🔍 SEO-friendly
- ♿ Accessible

## Sections

- **Home**: Eye-catching hero section with call-to-action
- **About**: Company information and key features
- **Services**: Overview of services offered
- **Contact**: Contact information

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- No external dependencies

## GitHub Pages Setup

To enable GitHub Pages for this repository:

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the `main` branch
4. Click "Save"
5. Your site will be published at: `https://arjun921.github.io/allwingroups.in/`

## Custom Domain Setup

This repository includes a `CNAME` file configured for `allwingroups.in`. To use your custom domain:

### Step 1: Configure DNS Records

Add the following DNS records at your domain registrar (where you bought allwingroups.in):

**For apex domain (allwingroups.in):**
```
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153
```

**For www subdomain (optional but recommended):**
```
Type: CNAME
Name: www
Value: arjun921.github.io
```

### Step 2: Enable Custom Domain in GitHub

1. Go to repository **Settings** → **Pages**
2. Under "Custom domain", enter: `allwingroups.in`
3. Click "Save"
4. Wait for DNS check to complete (may take a few minutes to 24 hours)
5. Check "Enforce HTTPS" once DNS is verified (for secure connection)

### Step 3: Verify

Once DNS propagates (usually 15 minutes to 24 hours), your site will be accessible at:
- `https://allwingroups.in`
- `https://www.allwingroups.in` (if you configured the CNAME record)

**Note**: The CNAME file in this repository tells GitHub Pages which custom domain to use. Don't delete it!

## Local Development

To view the site locally, simply open `index.html` in your web browser, or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with npx)
npx serve .
```

Then open `http://localhost:8000` in your browser.

## Customization

Feel free to customize:

- **Colors**: Modify CSS variables in `styles.css` (`:root` section)
- **Content**: Update text in `index.html`
- **Contact Info**: Replace placeholder contact details
- **Images**: Add your logo and images

## License

© 2025 Allwin Groups. All rights reserved.
