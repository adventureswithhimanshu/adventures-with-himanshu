# Adventures with Himanshu

Website for **Adventures with Himanshu**, boutique small-group trips across Meghalaya, Arunachal Pradesh and Mizoram in North-East India.

Live: https://adventureswithhimanshu.in

## Credits

- **Design & development:** [Piyush Kaushik](mailto:piyush.kaushik2@gmail.com)
- **Business owner:** Himanshu Pandey, ADVENTURES WITH HIMANSHU
- Some landscape photos via Unsplash

## Tech

A fast, dependency-free static site: one `index.html` with inline CSS and vanilla JavaScript, hosted on Netlify.

- Trips, regions, gallery and FAQs are plain data arrays inside `index.html`, so edits need no build step
- Enquiries go straight to WhatsApp or email, so there's no backend to maintain
- Responsive from small phones to desktop
- `_headers` sets the security headers (CSP) and caching

## Structure

```
index.html    the whole site
404.html      not-found page
_headers      Netlify security and cache headers
brand/        logo and favicons
images/       photos
videos/       intro video
```

## Editing and deploying

Edit `index.html` and push to `main`. Once Netlify is connected to this repository, it publishes automatically.

© ADVENTURES WITH HIMANSHU. All rights reserved. Code and design by Piyush Kaushik.
