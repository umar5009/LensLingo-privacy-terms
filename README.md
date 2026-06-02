# Legal pages (App Store)

Host these files so Privacy Policy and Terms URLs work in the app and App Store Connect.

## GitHub Pages (recommended)

1. Push this repo to GitHub (`umar5009/LensLingo`).
2. On GitHub: **Settings → Pages → Build and deployment → Source**: Deploy from branch `main`, folder **`/docs`**.
3. After deploy (~2 min), these URLs should work:

| Page | URL |
|------|-----|
| Privacy Policy | https://umar5009.github.io/LensLingo/legal/privacy.html |
| Terms of Service | https://umar5009.github.io/LensLingo/legal/terms.html |

4. Use the same URLs in **App Store Connect** (Privacy Policy URL + optional Terms link).

## Custom domain (optional)

Add `docs/CNAME` containing `lenslingo.app` and point DNS to GitHub Pages. Then update `AppLegalConfig.websiteBaseURL` in the app to `https://lenslingo.app` and copy `legal/*.html` to your server root.
