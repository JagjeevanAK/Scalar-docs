# Open Food Facts API Documentation

This project provides beautiful API documentation for the Open Food Facts API using Scalar.

## Project Structure

All static files must be inside the `public` directory for Vercel deployment:

```
public/
  index.html
  specfiles-json/
    openapi.json
    openapi-v3.json
    folksonomy-openapi.json
    kPanels-openapi.json
    open-prices-openapi.json
    robotoff-openapi.json
vercel.json
package.json
README.md
```

## Local Development

To run this locally:

```bash
npm install
npx serve public
```

Then open your browser to `http://localhost:3000` (or the port shown in terminal).

## Deployment to Vercel

### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```
2. Login to Vercel:
   ```bash
   vercel login
   ```
3. Deploy:
   ```bash
   vercel --prod
   ```
   Make sure your output directory is set to `public` in your Vercel project settings.

### Option 2: Deploy via GitHub (Recommended)

1. Push this code to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Set the output directory to `public` if prompted
6. Vercel will automatically deploy your static site
- ✅ Optimized for Vercel deployment
- ✅ Mobile-friendly design

## Configuration

The Scalar configuration in `index.html` includes:
- Local OpenAPI spec loading
- Modern theme and layout
- Custom CSS for better typography
- Sidebar navigation enabled

## API Documentation

This documentation covers the Open Food Facts API v2, including:
- Product information retrieval
- Product search functionality
- Image upload and management
- Authentication endpoints
- Personal search and preferences

Visit the deployed site to explore the full API documentation!
