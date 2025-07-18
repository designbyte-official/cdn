# Avatar CDN Repository

This repository provides a collection of avatar images that you can use directly in your projects via CDN delivery. Images are organized into folders for easy access, under the `main` branch and grouped by theme.

## How to Access Avatars via CDN


All images are accessible through jsDelivr CDN. Use the following URL structure (note the new organization under the `main` branch):

```
https://cdn.jsdelivr.net/gh/designbyte-official/cdn@main/<theme-folder>/<format>/<image-name>.<ext>
```

**Examples (click to open):**

- Cartoon avatar (JPG):  
  [https://cdn.jsdelivr.net/gh/designbyte-official/cdn@main/cartoon-avatars/jpg/1.jpg](https://cdn.jsdelivr.net/gh/designbyte-official/cdn@main/cartoon-avatars/jpg/1.jpg)
- Cartoon avatar (WebP):  
  [https://cdn.jsdelivr.net/gh/designbyte-official/cdn@main/cartoon-avatars/webp/1.webp](https://cdn.jsdelivr.net/gh/designbyte-official/cdn@main/cartoon-avatars/webp/1.webp)
- Human avatar (JPG):  
  [https://cdn.jsdelivr.net/gh/designbyte-official/cdn@main/human-avatars/jpg/3.jpg](https://cdn.jsdelivr.net/gh/designbyte-official/cdn@main/human-avatars/jpg/3.jpg)
- Human avatar (WebP):  
  [https://cdn.jsdelivr.net/gh/designbyte-official/cdn@main/human-avatars/webp/3.webp](https://cdn.jsdelivr.net/gh/designbyte-official/cdn@main/human-avatars/webp/3.webp)

**URL Structure:**
- `cdn@main` — The repository root and branch
- `<theme-folder>` — Either `cartoon-avatars` or `human-avatars`
- `<format>` — `jpg` or `webp`
- `<image-name>.<ext>` — The image file name (e.g., `3.jpg` or `3.webp`)

You can browse the folders in this repository to find the image numbers and formats you want to use.

## Folders
- `cartoon-avatars/` — Cartoon style avatars
- `human-avatars/` — Human faces avatars

## Excluded Files
- Python scripts and local environment files are excluded from the repo.
