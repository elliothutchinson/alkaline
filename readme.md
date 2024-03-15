# Alkaline - A Basic Pelican Theme Made with Tailwind

* [Live Preview](https://elliothutchinson.com)

## Setup

* Clone and add to Pelican project e.g. `<base_dir>/theme/alkaline`
* Set theme setting `THEME = "theme/alkaline"`

## Alkaline Theme Settings Example
```
ALK_PROFILE_IMG_URL = "images/me.jpg"
ALK_FOOTER_TEXT = "© 2016 - 2024 Elliot Hutchinson"
ALK_DEBUG_URLS = False
ALK_DISPLAY_BLOG_LINK = True
ALK_BLOG_URL = "blog"
ALK_DRAFTS_URL = "drafts"
ALK_PAGES_URL = "pages"
ALK_GITHUB_URL = "https://github.com/elliothutchinson"
ALK_LINKEDIN_URL = "https://linkedin.com/in/elliothutchinson"
ALK_SOCIAL_IMG_URLS = (
    ("images/linkedin.svg", "https://linkedin.com/in/elliothutchinson"),
    ("images/github.svg", "https://github.com/elliothutchinson"),
)
```

## Edit Tailwind CSS

* Install Node modules `npm install`
* Run Tailwind build `npm run build`
