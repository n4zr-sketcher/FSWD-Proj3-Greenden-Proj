# GreenDen

GreenDen is a responsive plant store website built with HTML and Tailwind CSS. The project presents artificial and natural plants through a clean, mobile-friendly shopping experience.

## Features

- Responsive navigation for desktop and mobile layouts
- Home page with hero section, store information, best sellers, reviews, and newsletter signup
- Product page with a plant catalog and product search field
- Contact page with a customer enquiry form
- Hover effects and responsive product grids
- Plant imagery stored locally in the `assests` folder

## Pages

- [Home](index.html)
- [Products](product.html)
- [Contact](contact.html)

## Built With

- HTML5
- Tailwind CSS v4
- Tailwind CSS CLI

## Project Structure

```text
.
├── index.html
├── product.html
├── contact.html
├── assests/
│   └── plant images
├── src/
│   ├── input.css
│   └── output.css
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js and npm

### Installation

1. Clone the repository:

	```bash
	git clone https://github.com/your-username/your-repository-name.git
	cd your-repository-name
	```

2. Install the dependencies:

	```bash
	npm install
	```

3. Start the Tailwind CSS watcher:

	```bash
	npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
	```

4. Open `index.html` in your browser, or use a local development server such as the VS Code Live Server extension.

## Customization

Edit the HTML files to update the page content and product details. Add or replace plant images in `assests/`, then update the corresponding image paths in the HTML files.