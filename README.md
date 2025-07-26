# MeeFun - Corporate Website

A modern, responsive corporate website for Guangzhou Miqu Information Technology Co., Ltd. Built with Jekyll and designed with a focus on technology and innovation.

## 🚀 Features

- **Modern Design**: Clean, professional design with a tech-focused aesthetic
- **Responsive Layout**: Fully responsive design that works on all devices
- **Fast Performance**: Optimized for speed and SEO
- **Interactive Elements**: Smooth animations and hover effects
- **Contact Form**: Integrated contact form for lead generation
- **SEO Optimized**: Meta tags, Open Graph, and structured data
- **Accessibility**: WCAG compliant with proper focus states and screen reader support

## 🎨 Design Highlights

- **Tech-Inspired Color Scheme**: Deep blues and cyan gradients
- **MeeFun Branding**: Custom logo design with "MF" initials
- **Smooth Animations**: CSS animations and transitions throughout
- **Modern Typography**: Inter font family for clean readability
- **Glass Morphism**: Subtle backdrop blur effects

## 📱 Pages

1. **Home** (`/`) - Hero section, services overview, company introduction
2. **About** (`/about/`) - Company story, mission, vision, and values
3. **Services** (`/services/`) - Detailed service offerings and development process
4. **Contact** (`/contact/`) - Contact form and company information

## 🛠️ Technology Stack

- **Jekyll** - Static site generator
- **HTML5/CSS3** - Modern web standards
- **JavaScript** - Interactive functionality
- **Google Fonts** - Inter font family
- **Formspree** - Contact form handling

## 🚀 Getting Started

### Prerequisites

- Ruby (2.4 or higher)
- RubyGems
- GCC and Make

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/meefun-website.git
cd meefun-website
```

2. Install dependencies:
```bash
bundle install
```

3. Start the development server:
```bash
bundle exec jekyll serve
```

4. Open your browser and navigate to `http://localhost:4000`

## 📁 Project Structure

```
├── _config.yml          # Jekyll configuration
├── _includes/           # Reusable components
│   ├── header.html      # Navigation header
│   └── footer.html      # Site footer
├── _layouts/            # Page layouts
│   └── default.html     # Default page layout
├── _posts/              # Blog posts (if needed)
├── _site/               # Generated site (don't edit)
├── about.markdown       # About page
├── contact.markdown     # Contact page
├── index.markdown       # Home page
├── services.markdown    # Services page
└── README.md           # This file
```

## 🎯 Customization

### Company Information

Update company details in `_config.yml`:

```yaml
title: MeeFun - Joy is Yours to Discover
email: support@meeefun.com
company_name: "Guangzhou Miqu Information Technology Co., Ltd."
slogan: "Joy is Yours to Discover"
```

### Colors and Styling

The main color scheme is defined in CSS variables throughout the site:

- Primary: `#00d4ff` (Cyan)
- Secondary: `#ff6b6b` (Coral)
- Dark: `#0f0f23` (Deep Blue)
- Light: `#f8f9fa` (Light Gray)

### Contact Form

The contact form uses Formspree. Update the form action in `contact.markdown`:

```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## 🌐 Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main` or `master`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify

1. Connect your GitHub repository to Netlify
2. Build command: `bundle exec jekyll build`
3. Publish directory: `_site`
4. Deploy automatically on push

### Vercel

1. Import your GitHub repository to Vercel
2. Framework preset: Other
3. Build command: `bundle exec jekyll build`
4. Output directory: `_site`

## 📈 SEO Optimization

- Meta descriptions for all pages
- Open Graph tags for social sharing
- Structured data markup
- Semantic HTML structure
- Fast loading times
- Mobile-friendly design

## 🔧 Development

### Adding New Pages

1. Create a new `.markdown` file in the root directory
2. Add front matter:

```yaml
---
layout: page
title: Page Title
permalink: /page-url/
---
```

3. Add your content in Markdown or HTML

### Styling

- Use CSS Grid and Flexbox for layouts
- Follow BEM methodology for CSS classes
- Maintain consistent spacing and typography
- Test on multiple devices and browsers

## 📞 Support

For questions or support, contact:
- Email: support@meeefun.com
- Company: Guangzhou Miqu Information Technology Co., Ltd.

## 📄 License

This project is proprietary to Guangzhou Miqu Information Technology Co., Ltd.

---

**Built with ❤️ by MeeFun Team** 