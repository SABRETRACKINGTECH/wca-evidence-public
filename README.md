# PublicSite

This folder contains simple static pages you can publish for:

- Privacy Policy
- Terms of Use
- Support

## Before publishing

1. Open `support.html`.
2. Replace `support@yourdomain.com` with your real public support email.
3. Replace `https://yourdomain.com/support` with the final public support page URL.
4. Review the policy and terms text to make sure it matches your real upload, retention, and support model.

## Quick publish options

### GitHub Pages

1. Create a GitHub repository.
2. Upload the files in this folder.
3. Turn on GitHub Pages in the repository settings.
4. Your URLs will look something like:
   - `https://yourname.github.io/repo/privacy.html`
   - `https://yourname.github.io/repo/terms.html`
   - `https://yourname.github.io/repo/support.html`

### Your own website

Upload these files to your web host and point your app links to:

- `https://yourdomain.com/privacy.html`
- `https://yourdomain.com/terms.html`
- `https://yourdomain.com/support.html`

## After publishing

Update `/Users/reynoldsfamilymac/Documents/War Crimes Atrocities WCA APP/Sources/Core/Support/AppReleaseInfo.swift`
with the live HTTPS URLs, then archive and upload a new build.
