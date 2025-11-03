# Service Not Available Page

A lightweight, mobile-friendly static HTML page to inform users that a service is not available in their region.

## Features

- **Lightweight**: Single HTML file with inline CSS (~3KB)
- **Fast Loading**: No external dependencies
- **Mobile-Friendly**: Responsive design that works on all devices
- **Generic**: Easy to customize for different services
- **GitHub Pages Ready**: Deploy instantly

## Usage

This page is designed to be used as a redirect target when users from certain countries visit your website.

### Customization

Edit `index.html` to customize:
- **Email**: Change `support@fixblur.com` to your support email
- **Colors**: Modify the gradient in the `body` and `.icon` styles
- **Text**: Update the message to match your needs
- **Icon**: Replace the 🌍 emoji with any other emoji or remove it

## Deployment

### GitHub Pages

1. Push this repository to GitHub
2. Go to repository Settings → Pages
3. Select the branch (usually `main`) and root folder
4. Your page will be available at `https://yourusername.github.io/repository-name/`

### Custom Domain

To use with a custom domain:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings in your domain registrar
3. Enable HTTPS in GitHub Pages settings

## Browser Support

Works on all modern browsers including:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Free to use and modify for any purpose.
