# Envision Print Services — Allyant portal

Static landing page for Envision Print Services (braille business cards, flyers, and custom braille projects).

## Structure

```
public/
  allyantbraille/   # everything lives here so the page works at workwithenvision.com/allyantbraille
    index.html      # the page (inline CSS + a small script that renders the braille dots)
    favicon.svg
    images/         # logos and photos
vercel.json         # serves public/ with no build step; / redirects to /allyantbraille
```

## Deploy to Vercel

1. In Vercel, choose **Add New → Project** and import this GitHub repository.
2. Leave the framework preset as **Other**. `vercel.json` already sets the output directory to `public` and skips the build.
3. Click **Deploy**.

Or from the command line:

```bash
npx vercel --prod
```

## Preview locally

```bash
npx serve public
```
