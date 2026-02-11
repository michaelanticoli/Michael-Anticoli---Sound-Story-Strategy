
  # Michael Anticoli - Sound, Story, Strategy

  This is a code bundle for Michael Anticoli - Sound, Story, Strategy. The original project is available at https://www.figma.com/design/bDr1UxXTxplNkADEtEyccQ/Michael-Anticoli---Sound--Story--Strategy.

  ## Running the code

  Run `npm i` to install the dependencies.

  Run `npm run dev` to start the development server.

  ## Deployment

  This project is configured for automatic deployment to GitHub Pages.

  ### GitHub Pages Setup

  1. Go to your repository's **Settings** → **Pages**
  2. Under "Build and deployment", set:
     - **Source**: GitHub Actions
  3. Push any changes to the `main` or `master` branch to trigger automatic deployment

  The GitHub Actions workflow (`.github/workflows/deploy.yml`) will automatically:
  - Install dependencies
  - Build the project
  - Deploy to GitHub Pages

  Your site will be available at: `https://michaelanticoli.github.io/Michael-Anticoli---Sound-Story-Strategy/`

  ### Manual Build

  To build the project manually:

  ```bash
  npm run build
  ```

  The built files will be in the `build/` directory.
  