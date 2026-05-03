# Ultranex US — Static Assets

Static files (JSON content + images) served via GitHub Pages for the Ultranex DTF US website.

## Structure

```
ultranex-us/
  data/          ← JSON content files
    site.json
    home.json
    about.json
    contact.json
    dtf-film-roll.json
    sustainability.json
    products.json

  images/        ← All site images
    features/    ← Feature section images (10 items)
    about/       ← About page facility photos
    team/        ← Team member photos
    *.jpg/png    ← Root-level images (composition, certificates, etc.)
```

## Base URL

Once deployed: `https://<username>.github.io/web-static-files/`

Example usage:
- `<base>/ultranex-us/data/home.json`
- `<base>/ultranex-us/images/features/quick-ink-drying.png`
- `<base>/ultranex-us/images/team/bhavesh-shah.jpg`
