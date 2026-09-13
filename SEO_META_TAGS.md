# SEO Meta Tags Reference — tourism-travel-001

## Essential Meta Tags (add to index.html <head>)

```html
<!-- Primary Meta Tags -->
<title>Tourism Travel 001 - Pack Light. Travel Far.</title>
<meta name="title" content="Tourism Travel 001 - Pack Light. Travel Far." />
<meta
  name="description"
  content="Explore curated travel packages, compare itineraries, and book securely online. Your dream trip starts here."
/>
<meta
  name="keywords"
  content="tour packages, travel booking, holidays, itinerary, adventure trips"
/>
<meta name="robots" content="index, follow" />
<meta name="language" content="English" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link rel="canonical" href="https://www.tourism-travel-001.com" />

<!-- Open Graph / Facebook -->
<meta property="og:type" content="website" />
<meta property="og:url" content="https://www.tourism-travel-001.com" />
<meta property="og:title" content="Tourism Travel 001 - Pack Light. Travel Far." />
<meta
  property="og:description"
  content="Curated packages and instant booking. Your next adventure awaits."
/>
<meta property="og:image" content="https://www.tourism-travel-001.com/og-image.jpg" />

<!-- Twitter Card -->
<meta property="twitter:card" content="summary_large_image" />
<meta property="twitter:url" content="https://www.tourism-travel-001.com" />
<meta property="twitter:title" content="Tourism Travel 001 - Pack Light. Travel Far." />
<meta
  property="twitter:description"
  content="Curated packages and instant booking. Your next adventure awaits."
/>
<meta property="twitter:image" content="https://www.tourism-travel-001.com/twitter-image.jpg" />

<!-- JSON-LD Structured Data -->
<script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "Tourism Travel 001",
    "url": "https://www.tourism-travel-001.com",
    "description": "Curated packages and instant booking. Your next adventure awaits.",
    "foundingDate": "2026",
    "contactPoint": {
      "@type": "ContactPoint",
      "contactType": "customer service",
      "availableLanguage": ["English", "Urdu"]
    },
    "sameAs": [
      "https://www.facebook.com/tourism-travel-001",
      "https://www.instagram.com/tourism-travel-001",
      "https://twitter.com/tourism-travel-001"
    ]
  }
</script>
```

## Multilingual (hreflang) — Add if i18n enabled

```html
<link rel="alternate" hreflang="en" href="https://www.tourism-travel-001.com/" />
<link rel="alternate" hreflang="ur" href="https://www.tourism-travel-001.com/ur/" />
<link rel="alternate" hreflang="ar" href="https://www.tourism-travel-001.com/ar/" />
<link rel="alternate" hreflang="x-default" href="https://www.tourism-travel-001.com/" />
```

## PWA Meta Tags — Add if PWA enabled

```html
<link rel="manifest" href="/manifest.json" />
<meta name="theme-color" content="#0d9488" />
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="default" />
<meta name="apple-mobile-web-app-title" content="Tourism Travel 001" />
```
