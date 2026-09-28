# FRAMZONE - Vercel Speed Insights Setup

This project has been configured with Vercel Speed Insights to monitor web performance.

## What was installed

- `@vercel/speed-insights` v2.0.0 - Official Vercel Speed Insights package
- `vite` v5.0.0 - Build tool for development and production

## Files created/modified

1. **package.json** - Created with project dependencies and scripts
2. **vite.config.js** - Vite configuration for building the project
3. **main.js** - Initializes Vercel Speed Insights
4. **index.html** - Added Speed Insights module script
5. **about.html** - Added Speed Insights module script (renamed from README.md)
6. **.gitignore** - Standard ignore file for Node.js projects

## How it works

The Speed Insights integration uses the `injectSpeedInsights()` function from the `@vercel/speed-insights` package. This function:

1. Automatically loads the Speed Insights script
2. Collects Core Web Vitals (LCP, FID, CLS, TTFB, FCP)
3. Sends performance data to Vercel for analysis
4. Works in both development and production environments

## Development

```bash
npm run dev      # Start development server at http://localhost:5173
npm run build    # Build for production
npm run preview  # Preview production build
```

## Deployment

When deployed to Vercel, Speed Insights will automatically start collecting data. You can view the analytics in your Vercel dashboard under the "Speed Insights" tab.

## Documentation

For more information, visit: https://vercel.com/docs/speed-insights
