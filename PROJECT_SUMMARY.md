# Project Analysis Summary

## Project Overview

This is a **personal academic portfolio website** for Hannah Attar, a Master's student in Financial Engineering at the University of Southern California. The site is hosted on GitHub Pages with a custom domain (`hannahattar.com`) and serves as a professional showcase of academic research, projects, and professional experience.

## Project Structure

### Core Files
- **`index.html`** - Homepage with bio, research interests, and personal introduction
- **`projects.html`** - Portfolio page showcasing 5+ research projects with metrics and tags
- **`experience.html`** - Professional experience timeline (Galliott Capital Advisors, freelance consulting, accounting)
- **`state-aware-model-risk.html`** - Detailed project page for the regime-aware model risk visualization project
- **`styles.css`** - Comprehensive CSS with custom properties, responsive design, and modern UI components
- **`CNAME`** - Custom domain configuration for GitHub Pages

### Assets
- **PDFs**: Research papers, resume, book manuscript preview
- **Images**: Project visualizations (5 PNGs for regime-aware project), book cover, profile photo
- **Other**: Project figure assets with descriptive filenames

## Content Analysis

### Academic Focus Areas
1. **Probability and Stochastic Processes** - Core mathematical frameworks
2. **Cross-Asset Correlations** - Market behavior and environmental signals
3. **Risk and Uncertainty** - Risk propagation and tail events
4. **Macroeconomic Dynamics** - Regime shifts and structural changes

### Featured Projects

1. **Regime-Aware Model Risk Visualization** (Primary)
   - Python-based machine learning project
   - Uses Gaussian Mixture Models and Logistic Regression
   - SPY daily data analysis (2006-2025)
   - Includes detailed visualization page with 5 figures
   - Metrics: 0.552 OOS Accuracy, 0.247 Brier Score, 0.66 Sharpe

2. **Spatial Econometric Modeling of Housing Markets**
   - Stata and Python workflow
   - Published on arXiv
   - Metrics: 0.891 R², 0.363 RMSE, 0.293 MAE

3. **Mortgage and MBS Cash-Flow Modeling**
   - Excel-based financial modeling
   - Amortization, prepayment, default analysis

4. **Probability and Stochastic Processes Book Manuscript**
   - LaTeX and Python
   - Educational reference work

5. **Development Economics Research** (D.R.C.)
   - Institutional analysis paper

## Technical Implementation

### Architecture
- **Type**: Static HTML/CSS/JavaScript website
- **Hosting**: GitHub Pages with custom domain
- **No build process**: Direct HTML/CSS deployment
- **Responsive design**: Mobile-first with breakpoints at 900px and 860px

### Design System
- **Color Palette**: Professional finance-oriented scheme
  - Background: Cool gray-blue (`#f5f7fb`)
  - Accent: Deep navy-blue (`#1e40af`)
  - Muted text: Calmer gray (`#52606d`)
- **Typography**: Lato font family (Google Fonts)
- **Layout**: Two-column grid (sidebar + main content)
- **Components**: Cards, buttons, callouts, figures, metrics displays

### Key Features
- **Sticky navigation bar** with backdrop blur effect
- **Sidebar profile** with avatar, bio, and contact links
- **Project cards** with hover effects, tags, metrics, and links
- **Detail pages** for in-depth project exploration
- **Responsive grid layouts** for project displays
- **Professional typography** with careful spacing and hierarchy

### CSS Architecture
- CSS custom properties (variables) for theming
- Modular component classes (`.project-card`, `.detail-section`, `.callout`)
- Responsive breakpoints using media queries
- Modern CSS features (Grid, Flexbox, backdrop-filter)

## Design Patterns

### Navigation
- Consistent top navigation across all pages
- Breadcrumb-style back links on detail pages
- Footer with dynamic year via JavaScript

### Content Organization
- **Projects page**: Card-based layout with metrics, tags, and descriptions
- **Experience page**: Chronological timeline with bullet points
- **Detail pages**: Hero section with metadata, abstract, results with figures

### Visual Hierarchy
- Clear typographic scale (h1: 34px, h2: 21px)
- Muted colors for secondary information
- Card-based content blocks with shadows and borders
- Figure components with captions

## Strengths

1. **Professional presentation** - Clean, modern design appropriate for academic portfolio
2. **Comprehensive content** - Well-organized projects with metrics and documentation
3. **Responsive design** - Works across device sizes
4. **Accessibility considerations** - Semantic HTML, proper alt text, focus states
5. **Performance** - Static site, minimal dependencies, optimized assets
6. **Maintainability** - Simple structure, no complex build tools

## Technical Notes

- Uses vanilla JavaScript (minimal, just for dynamic year)
- No JavaScript frameworks or libraries
- External dependencies: Google Fonts (Lato)
- All styling in single CSS file with good organization
- PDFs and images stored alongside HTML files

## File Organization

```
hannahattar.github.io/
├── HTML pages (4 main pages)
├── styles.css (single stylesheet)
├── Assets/
│   ├── PDFs (research papers, resume)
│   ├── Images (project figures, photos, covers)
│   └── CNAME (domain config)
└── README.md (minimal, just repository name)
```

## Recommendations for Future Enhancements

1. **SEO optimization** - Add meta tags, Open Graph tags
2. **Analytics** - Consider adding privacy-friendly analytics
3. **Performance** - Image optimization, lazy loading
4. **Accessibility** - ARIA labels, skip links, keyboard navigation improvements
5. **Content management** - Consider a simple static site generator if content grows
6. **Version control** - Ensure proper .gitignore for sensitive files

## Summary

This is a well-executed, professional academic portfolio website that effectively showcases quantitative finance research and experience. The codebase is clean, maintainable, and follows modern web development practices while remaining simple and performant. The design is appropriate for an academic context, and the content demonstrates strong technical and research capabilities in financial engineering, econometrics, and quantitative modeling.

