# MyBudDoc — improved static site (SEO + privacy/terms + sitemap)
Included: index, privacy, terms, consent.pdf, styles, og-image, favicon, robots, sitemap, 404.

Deploy (Cloudflare Pages):
1) Push to GitHub. 2) Cloudflare Pages → Create project → Connect to Git. 3) Framework: None; Build: blank; Output: /. 4) Add custom domain mybuddoc.com, enable HTTPS.

Suggested headers (set in Cloudflare):
- Strict-Transport-Security: max-age=31536000; includeSubDomains; preload
- Referrer-Policy: strict-origin-when-cross-origin
- X-Content-Type-Options: nosniff
- Permissions-Policy: interest-cohort=()

HIPAA: Do not collect PHI on site. After scheduling, send secure HIPAA intake/e-sign via a vendor with a BAA (DocuSign Enterprise, IntakeQ, Formstack HIPAA, SimplePractice, Jane, Jotform HIPAA).

Last updated: 2025-08-31a
