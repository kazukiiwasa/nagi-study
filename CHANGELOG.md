# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2025-12-21

### Changed

- Updated Astro from 5.16.0 to 5.16.6 ([see Astro changelog](https://github.com/withastro/astro/blob/main/packages/astro/CHANGELOG.md#5166))

### Fixed

- Limited works display on homepage to 4 items for better layout consistency

## [1.0.0] - 2025-12-07

Initial release of Nagi Inc. corporate website.

### Features

#### Pages

- **Homepage**: Hero section, services overview, works showcase, partner logos, and CTA
- **About Page**: Company introduction and team information
- **Company Page**: Detailed business information and company profile
- **Services Page**: Service descriptions with FAQ section
- **Works Page**: Portfolio listing with case studies
- **Work Detail Pages**: Individual project showcases
- **News Page**: News articles listing
- **News Detail Pages**: Individual news articles
- **Contact Page**: Contact form with validation
- **Contact Completion Page**: Thank you page after form submission
- **404 Page**: Custom error page
- **Privacy Policy Page**: Privacy policy information

#### Technical Features

- **Responsive Design**: Mobile-first approach with breakpoints at 600px and 900px
- **View Transitions**: Smooth page navigation using Astro View Transitions
- **Animation System**: Scroll-based reveal animations with customizable delays
- **SEO Optimization**:
  - Proper meta tags (title, description, OGP, Twitter Cards)
  - Canonical URLs
  - Schema.org structured data (Organization, WebSite)
  - Sitemap generation
- **Google Analytics**: Integration ready with configurable tracking ID
- **Accessibility**: Proper semantic HTML and ARIA labels
- **Performance**: Optimized images with WebP format and responsive loading

#### Design System

- **CSS Custom Properties**: Design tokens for colors, spacing, typography
- **SCSS Modules**: Component-scoped styling
- **Typography**: Google Fonts integration (Noto Sans JP, Inter)
- **Iconography**: Custom SVG icons
- **Color Scheme**: Professional dark theme with primary accent colors

[1.0.1]: https://github.com/yourusername/project/releases/tag/v1.0.1
[1.0.0]: https://github.com/yourusername/project/releases/tag/v1.0.0
