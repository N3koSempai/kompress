# Klia Kompress

**Klia Kompress** is a desktop image compression and conversion tool built for privacy, speed, and quality. Everything runs locally on your machine — no uploads, no cloud, no servers.

---

## What it does

Klia Kompress lets you drag in your images and convert them to modern formats with full control over quality and output destination. It handles individual files and batches, and gives you a live before/after comparison so you can see exactly what you're getting before you save.

### Supported output formats

| Format | Best for |
|--------|----------|
| **WebP** | Web use — great balance of quality and size |
| **AVIF** | Maximum compression — smallest files |
| **JPEG** | Universal compatibility |
| **PNG** | Lossless — no quality loss |

---

## EXIF metadata preservation

One of Klia Kompress's standout features is its ability to carry your photo's metadata through the conversion process — including when converting to formats that traditionally strip it.

When you compress or convert an image, Klia Kompress can preserve:

- **Camera model and lens information**
- **Date and time the photo was taken**
- **GPS location data**
- **Copyright and author information**
- **Exposure settings** (aperture, shutter speed, ISO)

This works across all supported formats:

- **JPEG → WebP**: EXIF data is embedded in the WebP container
- **JPEG → AVIF**: EXIF data survives conversion to AVIF (Pro feature)
- **JPEG → PNG**: EXIF data is stored in the PNG eXIf chunk
- **WebP / PNG → any format**: existing metadata is extracted and re-embedded

This is especially useful for photographers who need to deliver compressed files for web without losing the metadata their clients or archives depend on.

---

## Free vs Pro

Klia Kompress is free to use with the following limits:

| Feature | Free | Pro |
|---------|------|-----|
| Batch processing | Up to 3 images at once | Unlimited |
| AVIF with EXIF metadata | — | ✓ |
| Save directly to original folder | — | ✓ |
| Trial period | 3 days full access | — |

**Pro license:** $12 USD / 6 months. Payment is made in USDT on the Ethereum network (ERC-20). The license is tied to your machine and can be restored after reinstalls on the same hardware.

---

## Privacy

All image processing happens on your device using your CPU. No image data, metadata, or file content is ever transmitted to any server. The only network activity is the blockchain payment verification when purchasing a Pro license.

---

## Platform

Available for **Linux** (Flatpak via Flathub).

---

## License

This software is proprietary. See [LICENSE_EULA.md](LICENSE_EULA.md) for the full End User License Agreement.

*© 2026 Alvaro Martinez ([@N3koSempai](https://github.com/N3koSempai)). All Rights Reserved.*
