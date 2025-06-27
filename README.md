# Open Food Facts API Documentation

This project provides beautiful API documentation for the Open Food Facts API using Scalar.

## Files

- `index.html` - Main HTML file that loads Scalar and renders the API documentation
- `openapi.json` - OpenAPI 3.1.0 specification for the Open Food Facts API
- `vercel.json` - Vercel deployment configuration
- `package.json` - Node.js project configuration

## Local Development

To run this locally:

```bash
npm install
npm run dev
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
   vercel
   ```

### Option 2: Deploy via GitHub (Recommended)

1. Push this code to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will automatically detect this as a static site and deploy it

### Option 3: Deploy via Vercel Dashboard

1. Zip this folder
2. Go to [vercel.com](https://vercel.com)
3. Drag and drop the zip file onto the deployment area

## Features

- ✅ Modern, responsive API documentation interface
- ✅ Interactive API explorer
- ✅ Proper CORS headers for API testing
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
