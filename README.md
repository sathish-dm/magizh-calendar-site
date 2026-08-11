# Magizh Calendar — support and privacy pages

Two static pages published with GitHub Pages, serving the URLs that the App
Store and Google Play require for every listing:

| Page | Purpose |
|---|---|
| `index.html` | Support URL — FAQ and contact |
| `privacy.html` | Privacy Policy URL |

Deliberately plain: no build step, no framework, no external requests — not
even a web font. The app itself makes no network requests, and the pages that
describe it should not either.

The app source lives in a separate private repository.

**Before store submission:** replace `CONTACT_EMAIL` in both files. Both stores
require a working support contact.
