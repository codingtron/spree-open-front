<div align="center">
  <h1>Spree Open Front</h1>
  <p><strong>A modern, open-source Next.js storefront theme built for Spree Commerce.</strong></p>

  <p>
    <a href="https://github.com[YOUR-USERNAME]/spree-open-front/blob/main/LICENSE">
      <img src="https://shields.io" alt="MIT License" />
    </a>
    <img src="https://shields.io" alt="Next.js" />
    <img src="https://shields.io" alt="Spree API v2" />
    <img src="https://shields.io" alt="PRs Welcome" />
  </p>

  <p>
    <a href="[LIVE-DEMO-URL]">Live Demo</a> •
    <a href="#features">Features</a> •
    <a href="#quick-start">Quick Start</a> •
    <a href="#contributing">Contributing</a>
  </p>
</div>

<br />

![Spree Open Front Preview](./public/preview.png)

## Overview

**Spree Open Front** is a free, customizable, and production-ready storefront theme designed specifically for headless [Spree Commerce](https://spreecommerce.org) backends. Built with the Next.js App Router, it delivers fast page loads, SEO-friendly product pages, and a clean shopping experience out of the box.

## Features

- ⚡ **Next.js App Router:** Server-side rendering (SSR) and static generation for optimal speed and SEO.
- 🛍️ **Complete E-Commerce Flow:** Product listings, faceted filtering, variant selection, slide-out cart, and checkout integration.
- 🎨 **Tailwind CSS Styling:** Easily customize colors, typography, and layout tokens to match any brand.
- 🔐 **Customer Accounts:** Order history, saved addresses, and authentication via Spree Storefront API v2.
- 📱 **Mobile-First & Accessible:** Responsive layouts tested across desktop and mobile viewports.
- 🧩 **Modular Architecture:** Clean TypeScript components ready to extend or swap.

## Tech Stack

- **Framework:** Next.js (App Router) & React
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Commerce Engine:** Spree Commerce (Storefront API v2)

## Quick Start

### Prerequisites
- Node.js `18.17` or higher
- A running **Spree Commerce** backend instance (v4.6+ / v5+)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com[YOUR-USERNAME]/spree-open-front.git
   cd spree-open-front
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or pnpm install / yarn install
   ```

3. **Configure environment variables:**
   Copy `.env.example` to `.env.local` and point it to your Spree backend:
   ```bash
   cp .env.example .env.local
   ```
   ```env
   NEXT_PUBLIC_SPREE_API_URL=https://your-spree-backend.com
   ```

4. **Start the development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```text
├── src/
│   ├── app/          # Next.js App Router pages & layouts
│   ├── components/   # Reusable UI & commerce components
│   ├── lib/          # Spree API client, fetchers & helpers
│   └── types/        # TypeScript interfaces for Spree resources
├── public/           # Static assets & theme previews
└── .env.example      # Environment variable template
```

## Roadmap

- [ ] Multi-currency & multi-locale support
- [ ] Wishlist functionality
- [ ] Stripe & PayPal express checkout components
- [ ] One-click Vercel deploy button

## Contributing

Contributions are welcome! Whether it's fixing a bug, improving documentation, or proposing a new theme component, feel free to open an issue or submit a pull request. Please read [CONTRIBUTING.md](./CONTRIBUTING.md) first.

## License

This project is open-source and available under the [MIT License](./LICENSE).

---

*Disclaimer: Spree Open Front is an independent, community-maintained open-source project and is not officially affiliated with or endorsed by Spree Commerce.*
