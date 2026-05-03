# Personal Portfolio Landing

A personal portfolio landing page built with Astro, featuring a hero section, three project cards showcasing your work, and a contact form for visitors to get in touch. This modern, fast-loading site is designed to make a great first impression and help you connect with potential clients or employers.

## Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The development server runs at `http://localhost:4321` by default.

## Deploy to Netlify

1. Push your repository to GitHub, GitLab, or Bitbucket
2. Log in to [Netlify](https://netlify.com) and click "Add new site" > "Import an existing project"
3. Connect your repository and configure the build settings:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
4. Click "Deploy site"

Alternatively, you can deploy manually:

```bash
npm run build
npx netlify deploy --prod --dir=dist
```

## License

This project is available under the MIT License. See the LICENSE file for details.
