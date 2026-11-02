# castbuddy-app

The compiled [CastBuddy](https://github.com/topazh1/castbuddy) web app, served to testers by GitHub Pages at:

https://topazh1.github.io/castbuddy-app/

(The alias https://dnbtpzguoudkjqvlmoau.supabase.co/functions/v1/app redirects here.)

This repo holds build output only — do not edit by hand. It is regenerated from the private `castbuddy` repo, from a clean checkout there:

```bash
scripts/deploy-pages.sh ../castbuddy-app
```

which builds the app (split into chunks, precached by a service worker so it opens instantly and offline) and replaces everything here except `.git`, `.github`, `.nojekyll` and this README. Then commit and push `main`. GitHub Pages redeploys automatically on every push (live about a minute later); an open copy of the app moves onto the new build by itself, but never in the middle of an import or a take. `.nojekyll` keeps Pages from running the files through Jekyll.
