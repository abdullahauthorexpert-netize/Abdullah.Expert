# Abdullah Abdulsalam — Book Editor

A static, single-page portfolio website for Abdullah Abdulsalam’s book-editing services.

## Files

- `public/index.html` — complete site source, including the existing design, client review, and social/contact links.
- `public/letter-we-never-sent-cover.png` — extracted front cover for the second portfolio book.
- `public/beautiful-character-messenger.pdf` — PDF for *The Beautiful Character of the Messenger of Mercy*.
- `public/letter-we-never-sent.pdf` — PDF for *The Letter We Never Sent*.
- `public/manus-routes.json` — managed website route declaration.

## Local preview

From the project root, run:

```sh
python3 -m http.server 3000 --directory public
```

The managed deployment is configured as static output from `public/` with no build step. Keep linked PDFs and the cover image alongside `index.html` so their relative URLs continue working.
