# Alireza Belal's Personal Website

This repository contains the source code for my personal website: https://alirezabelal.github.io.

## About This Site
This website is built using the **Contrast** theme for Jekyll and is hosted on **GitHub Pages**.  
The site has been updated with a new homepage, an English resume, publications and project pages.

## Running Locally
To run the site locally (Jekyll + Contrast theme), follow these steps:

```sh
# 1. Clone the repository (use the correct repo name)
git clone https://github.com/AlirezaBelal/alirezabelal.github.io.git
cd alirezabelal.github.io

# 2. (Optional) switch to the feature branch to preview the recent updates
git fetch origin
git checkout site-update-resume-publications

# 3. Install dependencies (requires Ruby and Bundler)
bundle install

# 4. Serve the site locally
bundle exec jekyll serve
# Open http://localhost:4000 in your browser
```

Notes:
- If you use a different workflow (e.g., a static index.html served directly), you can simply open `index.html` in a browser for a quick preview.
- If you run the Jekyll server and do not see the updated branch content, ensure you have checked out `site-update-resume-publications` locally.

## Contact / Repo owner
- GitHub: https://github.com/AlirezaBelal  
- Website: https://alirezabelal.github.io