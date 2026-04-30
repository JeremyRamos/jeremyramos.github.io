# Dad · Dev · Devoted Personal Website

A clean, fun personal homepage built with Jekyll.

## Quick Start

### 1. Install Jekyll
```bash
gem install bundler jekyll
bundle install
```

### 2. Run locally
```bash
bundle exec jekyll serve
# Visit http://localhost:4000
```

### 3. Deploy to GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://yourusername.github.io/repo-name`

### 4. Use a custom domain
1. Add a `CNAME` file in the root with your domain: `yourdomain.com`
2. Point your domain's DNS to GitHub Pages (see GitHub docs)
3. Update `url:` in `_config.yml`

## Customise

- **Name / bio** → Edit `index.html` hero section
- **Skills** → Add/remove `<span class="skill-tag">` items
- **Verse** → Swap out the quote in the `.verse-section`
- **Colours** → Edit CSS variables at the top of `<style>` in `index.html`
