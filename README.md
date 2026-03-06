# Portfolio — Thanh (Jonathan) Bui

A modern, single-page portfolio website showcasing 8 years of experience building Fiat-Crypto bridges and QR payment systems. Features 10 projects spanning crypto exchanges, DeFi protocols, payment gateways, and robotics.

## Live Demo

View the portfolio at: `https://<username>.github.io/<repo-name>/`

## Features

- **Interactive Project Galleries** — Image carousels with video demos and lightbox zoom
- **Responsive Design** — Optimized for desktop and mobile viewing
- **Video Modals** — Full-screen video playback for project demonstrations
- **Clean Architecture** — Event delegation, input validation, and separation of concerns
- **Security Hardened** — No inline event handlers, external link protection, input validation

## Tech Stack

- **HTML5** with semantic markup
- **Tailwind CSS** (via CDN) for utility-first styling
- **Vanilla JavaScript** — No frameworks, pure ES6+
- **Google Fonts** — Montserrat (headings) + Open Sans (body)
- **Material Symbols** for icons

## Projects Showcased

1. **XpressFlow** — B2B2C crypto QR payment gateway
2. **Client Portal** — Merchant dashboard for transaction monitoring
3. **NemoSwap** — Decentralized exchange with cross-chain bridging
4. **Remitano** — Centralized exchange (2M+ users)
5. **Cellzier** — LLM-powered Discord bot for device troubleshooting
6. **DCA Bot** — Automated dollar-cost averaging with AMM positions
7. **Robotics** — ROS/Gazebo simulations and deep learning projects
8. **Protean** — IoT wave energy monitoring system
9. **Mắt Thần** — Smart glasses for the visually impaired
10. **HDL USB 9090** — Low-cost data acquisition card

## Project Structure

```
├── index.html              # Main portfolio page
├── images/                 # Project screenshots and assets
│   ├── profile.jpg
│   ├── icon-transparent.png
│   ├── qr-payment/        # XpressFlow gallery
│   ├── client-portal/     # Portal screenshots
│   ├── dex/               # NemoSwap screenshots
│   ├── tracking/          # Remitano screenshots
│   ├── cellzier/          # Cellzier bot screenshots
│   ├── dca-bot/           # DCA bot screenshots
│   ├── robotics/          # Robotics simulations
│   ├── protean/           # Protean project images
│   ├── mat-than/          # Smart glasses photos
│   └── hdl-9090/          # DAQ card images
├── resume.pdf             # Downloadable CV
├── portfolio-content.md   # Project descriptions (source)
└── README.md
```

## Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Python
python3 -m http.server 8000

# Node.js (with npx)
npx http-server -p 8000

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`.

## Deployment to GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose the `main` branch and `/ (root)` directory
5. Click **Save**

Your portfolio will be live at `https://<username>.github.io/<repo-name>/`

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Personal portfolio project. All rights reserved.

## Contact

- **Email:** jonathan.tcbui@gmail.com
- **LinkedIn:** [thanhbui-jonathan](https://www.linkedin.com/in/thanhbui-jonathan/)
- **GitHub:** [congthanh184](https://github.com/congthanh184)
