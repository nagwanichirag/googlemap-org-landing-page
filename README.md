# googlemap.org domain-for-sale landing page

A static GitHub Pages recreation of the supplied reference design. Includes the blue gradient hero, the six domain metrics supplied by the owner, benefits section, $150 Buy It Now panel, offer form, success state, cookie-consent banner, and footer.

## Offer form email delivery

The form uses FormSubmit's AJAX endpoint to send submissions to `askdomainexpert@gmail.com`. After publishing, submit a test offer. FormSubmit will send an activation email to that inbox; click its confirmation link. Actual visitor submissions will not be delivered until that activation is completed. GitHub Pages itself does not send email.

## GitHub Pages deployment

1. Create a public repository, e.g. `googlemap-org-landing-page`.
2. Upload `index.html`, `CNAME`, and this README to the repository root.
3. Open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Under **Custom domain**, enter `googlemap.org` and save.
5. In GoDaddy DNS, replace the parked A record for `@` with these four GitHub Pages A records:
   - `185.199.108.153`
   - `185.199.109.153`
   - `185.199.110.153`
   - `185.199.111.153`
6. Change `www` CNAME to `<your-github-username>.github.io`.
7. Keep the GoDaddy NS and SOA records. Once GitHub Pages verifies the domain and DNS has propagated, enable **Enforce HTTPS**.

DNS propagation can take time; do not assume the site is live until the custom domain and HTTPS are verified.

## Owner-supplied metrics

The age, search-volume, TLD, domain-score and other metric values are reproduced as supplied by the domain owner. Ensure the supporting evidence is retained and available to prospective buyers if requested.

## Trademark and affiliation

The footer includes a clear statement that the domain is independently owned and is not affiliated with or endorsed by Google LLC. This disclaimer does not itself resolve trademark or domain-dispute risks; consider qualified legal advice before marketing or transferring the domain.
