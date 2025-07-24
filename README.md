# Stephen's Website

A simple, clean landing page hosted on GitHub Pages.

## 🚀 Quick Start

### Local Development

1. Clone this repository
2. Open `index.html` in your browser

That's it! No build process required - this is a simple static site.

## 📝 Customization

### Update Your Information

1. Edit `index.html`:
   - Change the name and tagline in the header
   - Update the about section with your personal information
   - Replace the social links with your actual profiles

2. Modify `styles.css` to change:
   - Colors and fonts
   - Layout and spacing
   - Animations and effects

## 🌐 Deployment to GitHub Pages

1. Push this code to a GitHub repository
2. Go to Settings → Pages in your repository
3. Under "Source", select "Deploy from a branch"
4. Choose your branch (usually `main`) and `/` (root) folder
5. Click "Save"

Your site will be available at: `https://[your-username].github.io/[repository-name]`

## 🔗 Connecting Your Squarespace Domain

To connect your Squarespace domain to GitHub Pages:

1. In your GitHub repository settings, go to Pages
2. Under "Custom domain", enter your domain (e.g., `yourdomain.com`)
3. In Squarespace:
   - Go to Settings → Domains → [Your Domain] → DNS Settings
   - Add the following A records pointing to GitHub's IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - If using `www`, add a CNAME record:
     - Host: `www`
     - Value: `[your-username].github.io`

4. Enable "Enforce HTTPS" in GitHub Pages settings (may take up to 24 hours)

## 📄 License

This project is open source and available under the MIT License.
