# Sanad Ride Hailing Assets

This directory contains square, padded logos for the **Sanad ride-hailing platform**, for places that need a square image: Google Chat webhook avatars and card images, Slack bots, social profiles, favicons and similar.

The mark takes about 60% of the width, so it stays inside the circle when a platform crops the image round (Google Chat does).

Source: `apps/web/public/branding/sanad-main-logo.svg` in the `lamah-co/sanad` repository. Colors: `#05312C` (background) and `#99CA3F` (green mark).

## 📄 Available Files

| File Name              | Description                                   | Raw URL                                                                                              |
|------------------------|-----------------------------------------------|------------------------------------------------------------------------------------------------------|
| `logo.png`             | 1024×1024, white mark on dark green           | `https://raw.githubusercontent.com/lamah-co/public-resources/main/sanad%20ride%20hailing/logo.png`             |
| `logo-256.png`         | 256×256, white mark on dark green             | `https://raw.githubusercontent.com/lamah-co/public-resources/main/sanad%20ride%20hailing/logo-256.png`         |
| `logo-transparent.png` | 1024×1024, green mark on transparent          | `https://raw.githubusercontent.com/lamah-co/public-resources/main/sanad%20ride%20hailing/logo-transparent.png` |

## 📄 Cached Files

| File Name              | Description                                   | Raw URL                                                                                              |
|------------------------|-----------------------------------------------|------------------------------------------------------------------------------------------------------|
| `logo.png`             | 1024×1024, white mark on dark green           | `https://cdn.jsdelivr.net/gh/lamah-co/public-resources@main/sanad%20ride%20hailing/logo.png`             |
| `logo-256.png`         | 256×256, white mark on dark green             | `https://cdn.jsdelivr.net/gh/lamah-co/public-resources@main/sanad%20ride%20hailing/logo-256.png`         |
| `logo-transparent.png` | 1024×1024, green mark on transparent          | `https://cdn.jsdelivr.net/gh/lamah-co/public-resources@main/sanad%20ride%20hailing/logo-transparent.png` |

## 💬 Google Chat webhook example

```json
{
  "cardsV2": [{
    "cardId": "sanad",
    "card": {
      "header": {
        "title": "Sanad",
        "imageUrl": "https://cdn.jsdelivr.net/gh/lamah-co/public-resources@main/sanad%20ride%20hailing/logo-256.png",
        "imageType": "CIRCLE"
      }
    }
  }]
}
```

---

✅ The directory name has spaces, so keep the `%20` in the URLs.
