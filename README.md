# QCTiP 2026 - Quantum Computing Theory in Practice

Conference website for **Quantum Computing Theory in Practice (QCTiP 2026)**, hosted by the University of Oxford.

This is a GitHub Pages site built with Jekyll using the Cayman theme.

## About the Conference

QCTiP 2026 is an international conference bringing together researchers, practitioners, and industry leaders to explore the latest advances in quantum computing, bridging theory and practice.

## Local Development

### Prerequisites

- Ruby (version 2.5 or higher)
- Bundler gem

### Setup and Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/qctipconf/qctipconf.github.io.git
   cd qctipconf.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the Jekyll server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

### Building the Site

To build the site without serving it:
```bash
bundle exec jekyll build
```

The generated site will be in the `_site` directory.

## Site Structure

- `index.md` - Homepage
- `about.md` - About the conference
- `program.md` - Conference program and schedule
- `venue.md` - Venue and travel information
- `contact.md` - Contact information
- `_config.yml` - Jekyll configuration
- `Gemfile` - Ruby dependencies

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## License

Content © 2024 QCTiP Conference Organizers
