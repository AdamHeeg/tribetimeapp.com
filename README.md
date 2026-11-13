# tribetimeapp.com

Static website for the TribeTime app, served by GitHub Pages at https://tribetimeapp.com.

| Page | URL | Used for |
|---|---|---|
| Home | `/` | Landing page |
| Privacy Policy | `/privacy.html` | Play Console → App content → Privacy policy |
| Delete account | `/delete-account.html` | Play Console → App content → Data deletion → web link |
| Support | `/support.html` | Play Console store listing → contact website |

No build step: edit the HTML/CSS and push to `main`.

## Hosting setup (one time)

1. Repo → Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
2. Custom domain: `tribetimeapp.com` (the `CNAME` file sets this).
3. DNS at the domain registrar:
   - `A` records for `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record for `www`: `<github-username>.github.io`
4. After DNS resolves, tick **Enforce HTTPS** in Settings → Pages.
