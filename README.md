# Bart van Arem NFC Contact Page

This is a tiny static contact page for an NFC business card. The NFC card should store the public URL of this page, not the full contact details.

## Edit the details

This version includes these contact links:

- Email: `B.vanArem@tudelft.nl`
- Phone: `+31-642422455`
- WhatsApp: `https://wa.me/31642422455`
- Signal: `https://signal.me/#p/+31642422455`
- LinkedIn: `https://www.linkedin.com/in/bartvanarem/`
- Google Scholar: `https://scholar.google.com/citations?user=DmY2Hv4AAAAJ&hl=nl&inst=16061989973938494330`
- University profile: `https://www.tudelft.nl/en/staff/b.vanarem/`

The email button uses `mailto:`, so a visitor's phone should open their email app directly.

## Profile photo

The profile photo is stored at `assets/profile.jpg`. It is a compressed square crop made from `1551457785931.jpg` for fast loading on mobile.

To replace it later, add a new square image at the same path and keep the filename `profile.jpg`.

## Deploy options

Good free options:

- Netlify: easiest manual upload. Drag this folder or the `index.html` file into Netlify Drop.
- GitHub Pages: best if you already use GitHub and want the page tied to a repository.
- Cloudflare Pages or Vercel: also good for static pages, especially with a custom domain.

After deployment, copy the final `https://...` page URL into NFC Tools and write it as a URL record.

## NFC tip

Store only the URL on the NFC card. It is easier to update later: edit the webpage once, and every card tap sees the new version.
