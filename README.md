# Magesh Shanmugam's CV Website

This is a modern, responsive CV website built with HTML, CSS, and JavaScript. The website is designed to be hosted on Azure Static Web Apps.

## Features

- Responsive design that works on all devices
- Modern and clean UI
- Print-friendly layout
- Azure Static Web Apps compatible
- Customizable profile picture
- Easy to maintain and update

## Project Structure

```
.
├── index.html          # Main HTML file
├── staticwebapp.config.json  # Azure Static Web Apps configuration
├── package.json        # Project configuration
├── .gitignore          # Git ignore file
└── README.md          # This file
```

## Deployment to Azure Static Web Apps

1. Create a new Azure Static Web Apps resource in the Azure Portal
2. Connect your GitHub repository
3. Configure the build settings:
   - Build Command: `npm run build` (leave empty for static site)
   - App Location: `/`
   - App Artifact Location: `/`
   - API Location: leave empty (no API)
4. Deploy the application

## Local Development

To run the website locally:

1. Open `index.html` in your web browser
2. Or use a local web server (recommended for testing):
   ```bash
   npx http-server
   ```

## Customization

To customize the CV:
1. Update the content in `index.html`
2. Modify the styles in the `<style>` section of `index.html`
3. Add your profile picture by replacing the image in the profile section

## License

MIT License
