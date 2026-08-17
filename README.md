# castbuddy-app

The compiled [CastBuddy](https://github.com/topazh1/castbuddy) web app, published here so the CastBuddy edge function can serve it to testers at:

https://dnbtpzguoudkjqvlmoau.supabase.co/functions/v1/app

This repo holds build output only — do not edit by hand. It is regenerated from the private `castbuddy` repo:

```bash
npx vite build --config vite.artifact.config.ts
```

then pushing the contents of `dist-artifact/` here.
