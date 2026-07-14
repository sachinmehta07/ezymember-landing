# ezymember-landing

A landing page for the EzyMember application—a membership management solution designed to simplify member registration, access control, and information management.

## Overview

EzyMember Landing is a static website that serves as the public-facing front-end for the EzyMember platform. It provides information about the application, helps, and privacy documentation for users and potential members.

## Features

- **Landing Page** (`index.html`) - Main landing page with application overview and call-to-action
- **Help Documentation** (`help.html`) - User guidance and frequently asked questions
- **Privacy Policy** (`privacy-policy.html`) - Legal privacy documentation
- **Brand Assets** - Application logo for branding and visual identity

## Project Structure

```
ezymember-landing/
├── README.md                    # Project documentation (this file)
├── index.html                   # Main landing page
├── help.html                    # Help and support page
├── privacy-policy.html          # Privacy policy page
└── app_logo_no_bg.png          # Application logo (PNG format)
```

## Getting Started

### Prerequisites
- A web browser to view the HTML files
- A local web server (optional, for development)

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/sachinmehta07/ezymember-landing.git
   cd ezymember-landing
   ```

2. Open in your browser:
   - Simply open `index.html` in your web browser, or
   - Use a local web server for better development experience:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (with http-server package)
     npx http-server
     ```

3. Access the site at `http://localhost:8000`

## Pages

### Landing Page (`index.html`)
The main entry point for the application. Contains hero section, feature highlights, and call-to-action elements.

### Help Page (`help.html`)
Provides user guidance, FAQs, and support documentation for members using the EzyMember platform.

### Privacy Policy (`privacy-policy.html`)
Legal documentation outlining data privacy, user rights, and information handling practices.

## Deployment

This static website can be deployed to various hosting platforms:

- **GitHub Pages** - Enable GitHub Pages in repository settings (main branch or docs folder)
- **Netlify** - Connect your GitHub repository for automatic deployments
- **Vercel** - Deploy directly from GitHub with zero-config
- **Traditional Web Hosting** - Upload files via FTP/SFTP to your web server

## Technologies Used

- **HTML** - Markup and structure
- **CSS** - Styling (embedded or external)
- **JavaScript** - Interactive elements (if applicable)
- **Images** - PNG logo assets

## Configuration

For site-wide configuration changes:
1. Update text, colors, and branding in HTML files
2. Replace `app_logo_no_bg.png` with updated logo if needed
3. Modify links and CTAs across all pages

## Contributing

To contribute to this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## License

This project is open source and available under the MIT License.

## Support

For issues, questions, or suggestions regarding the EzyMember landing page, please:
- Open an issue on the [GitHub repository](https://github.com/sachinmehta07/ezymember-landing/issues)
- Refer to the [Help page](help.html) for user documentation
- Review the [Privacy Policy](privacy-policy.html) for data handling information

## Author

Created and maintained by [sachinmehta07](https://github.com/sachinmehta07)

---

**Last Updated:** July 14, 2026