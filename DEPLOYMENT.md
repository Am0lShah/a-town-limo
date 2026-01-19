# Netlify Deployment Guide for A Town Limo

## Quick Deploy to Netlify

### Option 1: Direct GitHub Integration (Recommended)

1. **Go to Netlify**: Visit [netlify.com](https://netlify.com) and sign in
2. **New Site from Git**: Click "New site from Git"
3. **Connect to GitHub**: Choose GitHub as your Git provider
4. **Select Repository**: Choose `Am0lShah/a-town-limo`
5. **Deploy Settings**:
   - **Branch to deploy**: `main`
   - **Build command**: Leave empty (static site)
   - **Publish directory**: `.` (root directory)
6. **Deploy Site**: Click "Deploy site"

### Option 2: Manual Deploy

1. **Download Repository**: Download the repository as ZIP
2. **Extract Files**: Extract to a local folder
3. **Drag & Drop**: Go to Netlify and drag the folder to the deploy area

## Site Configuration

The `netlify.toml` file is already configured with:
- Security headers
- Cache optimization for assets
- Redirect rules
- Performance settings

## Custom Domain Setup (Optional)

1. **Domain Settings**: Go to Site settings > Domain management
2. **Add Custom Domain**: Click "Add custom domain"
3. **DNS Configuration**: Update your domain's DNS to point to Netlify
4. **SSL Certificate**: Netlify will automatically provision SSL

## Environment Variables (If Needed)

For future API integrations:
1. **Site Settings**: Go to Site settings > Environment variables
2. **Add Variables**: Add any required API keys or configuration

## Performance Optimizations Included

- ✅ Image optimization and lazy loading
- ✅ CSS and JS minification (browser-level)
- ✅ Gzip compression (Netlify automatic)
- ✅ CDN distribution (Netlify automatic)
- ✅ Mobile-first responsive design
- ✅ Optimized asset caching

## Post-Deployment Checklist

- [ ] Test all navigation links
- [ ] Verify mobile responsiveness
- [ ] Test booking form functionality
- [ ] Check image loading and video playback
- [ ] Validate contact information
- [ ] Test phone number links
- [ ] Verify social media links (update with real URLs)

## Site URL

Once deployed, your site will be available at:
- **Netlify URL**: `https://[random-name].netlify.app`
- **Custom Domain**: Configure your own domain in Netlify settings

## Maintenance

- **Updates**: Push changes to the `main` branch for automatic deployment
- **Monitoring**: Use Netlify Analytics for traffic insights
- **Forms**: Enable Netlify Forms for contact form submissions

---

🚀 **Your A Town Limo website is now ready for deployment!**