# 🐧 Pelican Pages 

Static site generated with Pelican, deployed to GitHub Pages.

## Quick Start / Deployment

```bash
# 1. Activate virtualenv
source venv/bin/activate

# 2. Build locally
pelican content

# 3. Deploy output/ to gh-pages branch
ghp-import -n -p -f output

# 4. Preview locally (optional)
pelican -l -r
```

### But that's a penguin emoji...

¯\\_(ツ)_/¯