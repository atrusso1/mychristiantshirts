# My Christian Tshirts - Landing Page

A beautiful, professional landing page for My Christian Tshirts brand that directs visitors to our Shopify store.

## What's Included

- **index.html** - Complete landing page with navigation, hero section, features, product showcase, and call-to-action
- **Responsive Design** - Looks great on desktop, tablet, and mobile devices
- **Fast Loading** - No external dependencies, pure HTML and CSS
- **SEO Ready** - Meta tags and semantic HTML for better search engine visibility

## Features

✝️ **Faith-Centered Design** - Professional branding that reflects Christian values
🎨 **Modern Aesthetic** - Clean, contemporary design with intentional color choices
📱 **Fully Responsive** - Works perfectly on all devices
🚀 **Fast & Optimized** - Minimal code, maximum performance
🔗 **Direct to Shop** - Multiple CTAs that link directly to your Shopify store

## Customization

### Colors
The main brand color is `#d4a574` (warm gold). To change it, search and replace this color throughout the file.

### Text & Content
All text content is easy to find and edit directly in the HTML file. Update:
- Navigation links
- Hero headline and description
- Feature cards content
- Product information
- Email address in footer

### Images
The product images are currently linked from your Shopify CDN. To use different images, replace the image URLs in the `<img>` tags.

## Deployment with GitHub Pages

### Step 1: Create a GitHub Account
If you don't have one, go to [github.com](https://github.com) and sign up for free.

### Step 2: Create a New Repository
1. Go to [github.com/new](https://github.com/new)
2. Repository name: `mychristiantshirts.co`
3. Description: "Landing page for My Christian Tshirts"
4. Choose **Public** (required for GitHub Pages)
5. Click "Create repository"

### Step 3: Upload Your Files
1. In your new repository, click the "Add file" dropdown
2. Select "Upload files"
3. Drag and drop (or select) these files:
   - `index.html`
   - `CNAME` (if using custom domain)
4. Add a commit message: "Initial landing page"
5. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to your repository's Settings (top right)
2. Scroll down to "Pages" section (left sidebar)
3. Under "Source", select "Deploy from a branch"
4. Select branch: `main`
5. Select folder: `/ (root)`
6. Click "Save"

**Wait 2-5 minutes** for GitHub Pages to build your site. You'll see a green checkmark when it's ready.

### Step 5: Connect Custom Domain (www.mychristiantshirts.co)

#### Option A: You own the domain
1. Go to your domain registrar (GoDaddy, Namecheap, Google Domains, etc.)
2. Find DNS settings
3. Create an A record pointing to these GitHub IP addresses:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
4. Create a CNAME record:
   - Name: `www`
   - Points to: `yourusername.github.io`

#### Option B: Using the CNAME file (easier)
1. Back in your GitHub repository, you should already have a `CNAME` file
2. This file contains: `mychristiantshirts.co`
3. In GitHub Settings > Pages, add your domain in the "Custom domain" field
4. GitHub will check the DNS configuration and enable HTTPS when ready

### Step 6: Update Repository Settings (Optional)
In Settings:
- Add a custom domain in the "Pages" section
- Enable "Enforce HTTPS" once it becomes available

## Testing

After deployment:
1. Visit your GitHub Pages URL: `https://yourusername.github.io`
2. Visit your custom domain: `https://www.mychristiantshirts.co`
3. Test all links to ensure they go to your Shopify store
4. Check on mobile devices

## Making Updates

To edit your landing page:
1. Go to your GitHub repository
2. Click on `index.html`
3. Click the pencil icon (Edit)
4. Make your changes
5. Scroll down and click "Commit changes"
6. Changes will live in 1-2 minutes

## Support

For GitHub Pages help: [pages.github.com](https://pages.github.com)
For DNS help: Contact your domain registrar's support

---

**Questions?** Reach out to atrusso@protonmail.com

God bless! 🙏
