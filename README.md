# castbuddy-app

The compiled [CastBuddy](https://github.com/topazh1/castbuddy) web app, served to testers by GitHub Pages at:

https://topazh1.github.io/castbuddy-app/

(The alias https://dnbtpzguoudkjqvlmoau.supabase.co/functions/v1/app redirects here.)

This repo holds build output only — do not edit by hand. It is regenerated from the private `castbuddy` repo:

```bash
npx vite build --config vite.artifact.config.ts
```

then pushing the contents of `dist-artifact/` here. GitHub Pages redeploys automatically on every push to `main` (live about a minute later). `.nojekyll` keeps Pages from running the files through Jekyll.
