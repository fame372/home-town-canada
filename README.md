Table of Contents

Motivation

Features

Demo / Screenshots

Tech Stack

Getting Started

Prerequisites

Installation

Running Locally

Building / Deployment

Project Structure

Contributing

License

Acknowledgments

Motivation

Edmonton is a vibrant city with a lot to offer — from festivals to parks, arts, and local stories. This project is meant to:

Provide an attractive and informative web presence for Edmonton

Serve as a portfolio project to showcase front-end skills

Be easily extensible so new content or features (e.g., events, mapping) can be added

Features

Responsive design to support desktop and mobile

City highlights: attractions, galleries, history

Dynamic sections (e.g. “Things to do”, “Places”)

Clean UI / UX, animations or transitions (if applicable)

Easy to maintain & expand

Demo / Screenshots

(You can insert images or a GIF here to show what the site looks like.)

Tech Stack

Here’s a likely stack (adjust as per your actual implementation):

Frontend: HTML5, CSS (or SCSS / Tailwind / styled-components), JavaScript (or TypeScript)

Framework / Library: React / Vue / Svelte / plain JS (whatever your project uses)

Build Tool / Bundler: Vite, Webpack, Rollup, etc.

Hosting / Deployment: Netlify

Optional: APIs, content backend, CMS, image optimization

Getting Started
Prerequisites

Make sure you have installed:

Node.js (v14+, v16+, or as required)

npm or yarn

Installation

Clone the repo:

git clone https://github.com/yourusername/welcome-to-edmonton.git
cd welcome-to-edmonton


Install dependencies:

npm install
# or
yarn install

Running Locally

To run in development mode with hot reloading:

npm run dev
# or
yarn dev


Then open your browser to http://localhost:3000 (or the port your dev server uses).

Building / Deployment

To build for production:

npm run build
# or
yarn build


The output folder (e.g. dist or build) can be deployed to Netlify or any static host.

If using Netlify, you may need to configure settings like the publish directory and redirects (for SPAs).

Project Structure

Here’s an example of how your project folders/files might be organized:

.
├── public/
│   └── assets/        # images, icons, static files
├── src/
│   ├── components/    # reusable UI parts
│   ├── pages/         # page-level components or views
│   ├── styles/        # CSS, SCSS, or style files
│   ├── utils/         # helper functions
│   └── main.js / index.js
├── .gitignore
├── package.json
├── README.md
└── netlify.toml (if using Netlify config)


You can adjust structure based on your framework or preferences.

Contributing

Thank you for considering contributing! Here’s how to help:

Fork the repository

Create a new branch (git checkout -b feature/my-feature)

Make your changes & ensure you follow existing code style

Test your changes

Submit a Pull Request

Please include a description of your changes and any relevant screenshots or steps to verify.

License

Specify the license you prefer. For example:

MIT License

© 2025 Your Name


You can also add a LICENSE file with full license text.
