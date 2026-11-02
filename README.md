# Easy Meals website

Static website for Easy Meals, Kathmandu. Uses Outfit and Inter with the supplied brand logo and SVG icons.

## Local preview

Serve the `dist` folder with any static HTTP server, then open its local URL. No install or build step is required.

## Vercel

Import this repository into Vercel. Select Other for the framework, leave the build command empty, and set the output directory to `dist`. The included `vercel.json` declares these settings.

## Content

Page content and interactions are in `dist/app.js`, styles in `dist/style.css`, and shared markup in `dist/index.html`. The enquiry form prepares an email in the visitor's email application; it does not store or send enquiries through a server. Food photographs are illustrative stock imagery.

