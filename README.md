# Space by Day Design — SEO-Optimized Website

Static website for **Space by Day Design**, an interior design studio based in Lemont, IL serving the Chicago metro area.

## Deployment

This site is configured for **Netlify** deployment via GitHub integration.

1. Push this repo to GitHub
2. Connect the repo to Netlify
3. Netlify will auto-deploy from the root directory (no build step needed)

### Netlify Configuration

- **Publish directory:** `.` (root)
- **Build command:** (none — static HTML)
- **Custom domain:** `www.spacebyday.com`

## File Structure

```
├── index.html                          # Homepage (multi-page SPA)
├── sitemap.xml                         # XML sitemap for search engines
├── robots.txt                          # Crawler directives + sitemap reference
├── netlify.toml                        # Netlify deploy config, headers, redirects
├── _headers                            # Netlify flat-file headers (security + caching)
├── _redirects                          # Netlify redirects (clean URLs + old Wix redirects)
├── 404.html                            # Custom 404 error page
├── manifest.json                       # PWA manifest / favicon metadata
├── README.md                           # This file
└── .gitignore                          # Git ignore rules
```

## SEO Features

- **Keyword-optimized title tags & meta descriptions** on every page
- **Schema.org structured data** (InteriorDesignBusiness + Service)
- **Open Graph tags** for social media sharing
- **XML sitemap** for search engine indexing
- **Robots.txt** with sitemap reference
- **301 redirects** from old Wix URLs to preserve any existing link equity
- **Canonical URLs** on every page
- **Semantic HTML5** with proper heading hierarchy
- **Keyword-rich image alt text** on every image
- **Local SEO signals** (Lemont, IL + Chicago metro throughout)
- **Mobile-first responsive design**
- **Lazy loading** on below-fold images
- **Security headers** (X-Frame-Options, CSP, etc.)

## Pages

| Page | Target Keywords |
|------|----------------|
| Homepage | interior designer Chicago, 3D home renderings Lemont IL |
| Kitchen Remodel | kitchen remodel design Chicago, kitchen renovation visualization |
| Bathroom Renovation | bathroom renovation design Chicago suburbs |
| Basement Finishing | basement finishing design Chicago, finished basement visualization |
| Bedroom Design | bedroom interior design Chicago metro |
| Living Room Design | living room interior design Lemont IL |
| For Builders | builder design services Chicago, 3D renderings for contractors |
| Portfolio | interior design portfolio, photorealistic renderings Chicago |

## Post-Deploy Checklist

- [ ] Verify all pages load correctly on the custom domain
- [ ] Submit sitemap to [Google Search Console](https://search.google.com/search-console)
- [ ] Submit sitemap to [Bing Webmaster Tools](https://www.bing.com/webmasters)
- [ ] Set up Google Analytics or Plausible Analytics
- [ ] Create/update [Google Business Profile](https://business.google.com)
- [ ] Test with [Google PageSpeed Insights](https://pagespeed.web.dev)
- [ ] Test with [Google Rich Results Test](https://search.google.com/test/rich-results)
