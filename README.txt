Asterra AI - Vercel static deployment

This folder contains index.html, the entry point for Vercel static hosting.

Deploy:
1. Create a GitHub repository and upload index.html to its root.
2. In Vercel, choose Add New -> Project and import that GitHub repository.
3. Framework Preset: Other.
4. Build Command: leave blank.
5. Output Directory: .
6. Install Command: leave blank.
7. Click Deploy.

If the HTML references external libraries or map imagery, those resources still need to be reachable from the browser. This package does not include third-party services or API credentials.
