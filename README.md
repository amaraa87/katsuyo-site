# katsuyo-site

Public web pages for the **Katsuyō: Japanese Verbs** iOS app: landing page, privacy
policy and support, the URLs App Store Connect requires. Published to GitHub Pages by
`.github/workflows/pages.yml` on every push to `main`.

- Landing: https://amaraa87.github.io/katsuyo-site/
- Privacy policy: https://amaraa87.github.io/katsuyo-site/privacy/
- Support: https://amaraa87.github.io/katsuyo-site/support/

Plain HTML and one stylesheet (`assets/style.css`, colours from the app's `Theme.swift`
tokens). No JavaScript, no web fonts, no trackers. Links are relative, so the site works
under the `/katsuyo-site/` base path or a custom domain.

The privacy policy must match what the app actually does (1.0 makes no network requests
and collects no data), the App Privacy answers in App Store Connect ("Data Not Collected"),
and `PrivacyInfo.xcprivacy`. When one changes, update the others.
