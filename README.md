# Quantum Computing Theory in Practice (QCTiP)

Landing page for the **Quantum Computing Theory in Practice** conference series.

This is a GitHub Pages site built with Jekyll using the Cayman theme.

## About the Conference

QCTiP is the globally leading conference that focuses on practical aspects of quantum computing, bringing together researchers, practitioners, and industry leaders to explore the latest advances in quantum computing, bridging theory and practice.

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
   bundle exec jekyll serve --baseurl=""
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
- `committees.md` - details of the Steering Committee
- `programme.md` - Conference programme and schedule
- `events.md` - List of past QCTiP events
- `contact.md` - Contact information
- `_config.yml` - Jekyll configuration
- `Gemfile` - Ruby dependencies

## Deployment

The site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## License

Content © 2024 QCTiP Conference Organizers
