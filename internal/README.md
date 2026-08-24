# HAAT Builders (internal)

Internal POS guide for Market and Restaurant Content.

This is a **separate Mintlify site**. It is not part of the public partner docs.

**Intended live URL:** https://haat-internal.mintlify.app

## Local preview

From this folder:

```bash
npx mintlify dev --port 3001
```

Then open http://127.0.0.1:3001/builders/overview

## Deploy

1. In [Mintlify](https://app.mintlify.com), create a **new deployment** in the HAAT org.
2. Subdomain: `haat-internal` (or any unused name).
3. Connect the same GitHub repo as the public docs (`fhmedeknash/docs`).
4. In Git settings, turn on **docs.json is in a subdirectory** and set the path to `/internal`.
5. In [Authentication](https://app.mintlify.com/products/authentication), set the site to **Private** (Mintlify login, or a password). That keeps clients off this subdomain even if they guess the URL.
