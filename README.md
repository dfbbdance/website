# DFBB introduction website

Official bilingual introduction for DFBB Dance Crew, operated by DFBB Dance Inc.

Plain HTML and CSS, no build dependencies. Preview with `python3 -m http.server 8080` and open localhost:8080. Publish the root of `main` with GitHub Pages. Set the Pages custom domain to `dfbbdance.org` before adding website DNS records. Enable HTTPS after certificate issuance.

Keep mail DNS and Email Routing unchanged. Website records: apex A records 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; www CNAME dfbbdance.github.io, DNS only. Never use wildcard records.

Edit bilingual copy together in index.html. Brand colors are in style.css. Logo is an existing DFBB brand asset; no third-party license is granted. No donation, analytics, forms or embedded video. Links open the actual public platforms.

Rollback: revert a content commit and publish main. When moving hosting, retain dfbbdance.org and update only website DNS after the replacement is ready. Full website framework and contributor roles remain a separate review.
