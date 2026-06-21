# Oriz Pixie — Image tools

> Compress, resize, crop, convert, watermark, upscale, remove backgrounds, blur faces, generate memes — every operation runs in your browser.

**Live at**: https://image.oriz.in · **Status**: production

## What this is

A browser-based image toolkit. Your photos never travel over the network — every tool processes pixels locally. Sign-in is optional and only powers cross-app features.

## Per-feature inventory

| Feature | Status |
|---|---|
| Compress image | ✅ live |
| Resize image | ✅ live |
| Crop image | ✅ live |
| Rotate image | ✅ live |
| Convert to JPG | ✅ live |
| Convert from JPG | ✅ live |
| Watermark image | ✅ live |
| Blur face | ✅ live |
| Remove background | ✅ live |
| Upscale image | ✅ live |
| Photo editor | ✅ live |
| Meme generator | ✅ live |
| HTML to image | ✅ live |

## App-specific env vars

None beyond the family-wide set at `templates/.env.example`.

## Local dev

```bash
# from the workspace root (c:/D/oriz)
pnpm -F @chirag127/oriz-image-tools dev
```

## Knowledge

See [`./knowledge/`](./knowledge/) for app-specific decisions, runbooks, and services. Family rules / decisions / architecture live at the master repo's [`knowledge/`](../../../../knowledge/).

## License

Source-available, all rights reserved. See master [`LICENSE`](../../../../LICENSE) — same terms across the family.
