# SEO Optimization Guide

## Overview
This file documents the SEO optimizations added to the YouTube Buttons Shop website.

## Added SEO Meta Tags

The following meta tags were added to the `<head>` section of `index.html`:

### Description Meta Tag
```html
<meta name="description" content="Премиум-кнопки YouTube, Instagram, TikTok, VK, Telegram. Сделай свой канал или профиль уникальным! Собственное производство, доставка по РФ.">
```
**Purpose:** Provides a concise description of the website for search engines and social media previews.

### Keywords Meta Tag
```html
<meta name="keywords" content="кнопка YouTube купить, кнопка Instagram, премиум кнопка, подарок блогеру, заказать кнопку, кнопка TikTok, сувенир для блогера">
```
**Purpose:** Helps search engines understand the main topics of your website.

### Open Graph Tags (for Social Media)
```html
<meta property="og:title" content="YouTube Buttons Shop — Премиум кнопки для соцсетей">
<meta property="og:description" content="Эксклюзивные премиум-кнопки для YouTube, Instagram, VK, TikTok, Telegram.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://your-domain.com">
```
**Purpose:** Controls how your website appears when shared on social media platforms.

### Additional Meta Tags
```html
<meta name="robots" content="index, follow">
<meta name="language" content="Russian">
<meta name="author" content="YouTube Buttons Shop">
<link rel="canonical" href="https://your-domain.com">
```
**Purpose:** 
- `robots`: Tells search engines to index and follow links
- `language`: Specifies the website language
- `author`: Identifies the website owner
- `canonical`: Prevents duplicate content issues

## Schema.org Structured Data

A Store schema was added to help search engines understand your business:

```json
{
  "@context": "https://schema.org/",
  "@type": "Store",
  "name": "YouTube Buttons Shop",
  "description": "Премиум кнопки для социальных сетей",
  "url": "https://your-domain.com",
  "telephone": "+7 977 966-2521",
  "image": "https://your-domain.com/preview.jpg",
  "sameAs": [
    "https://www.instagram.com/youtube.buttons",
    "https://www.youtube.com/channel/youtube-buttons"
  ]
}
```

## Important: Next Steps

To fully implement these optimizations, you need to:

1. **Replace placeholder URLs**
   - Change `https://your-domain.com` to your actual domain
   - Update the preview image URL

2. **Update social links**
   - Add your actual Instagram and YouTube channel URLs

3. **Verify with Google**
   - Submit your sitemap to Google Search Console
   - Use the Rich Results Test to verify structured data
   - Check for any indexing issues

4. **Monitor Performance**
   - Track keyword rankings
   - Monitor organic traffic
   - Check for crawl errors

## SEO Best Practices

- Keep descriptions between 150-160 characters
- Use relevant keywords naturally
- Ensure all images have descriptive alt text
- Mobile-responsive design (already implemented)
- Fast page load times (optimize images and minify CSS/JS)
- Regular content updates

## Files Modified

- `index.html` - Added SEO meta tags and schema.org structured data

## Testing Tools

- [Google Rich Results Test](https://search.google.com/test/rich-results)
- [Google Page Speed Insights](https://pagespeed.web.dev/)
- [Yandex Metrica](https://metrica.yandex.com/)
- [SEMrush](https://www.semrush.com/)
