# Publish MACPodWebsite

Serve this repository's root using GitHub Pages: Settings → Pages → Deploy from a branch → master → / (root). Enable only after merging the website PR.

Before assigning the custom domain, verify marriaga.com ownership through your GitHub account Pages settings. Set the site's custom domain to macpod.marriaga.com. At your DNS provider add a CNAME record with name macpod and target MiguelArriaga.github.io. Keep other records unchanged. Once DNS and the certificate are ready, enable Enforce HTTPS.

Check index.html, privacy.html and terms.html at the custom domain. Use their public URLs in Google OAuth branding and verify domain ownership in Google Search Console as required.

Google OAuth registration and real-account backup/restore testing remain separate. Register the Android client for com.macpod.app and the retained master APK signing-certificate SHA-1. No client secrets belong in this website.

Review the privacy and terms wording before public launch. Support currently links to the developer's public GitHub profile; add a suitable direct public contact if required by Google's registration flow. This change publishes no personal email address.

No dependencies or build command are needed. No analytics scripts or external assets are loaded. GitHub Pages hosting processes ordinary website requests.
