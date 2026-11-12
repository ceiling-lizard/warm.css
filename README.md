# warm.css

A drop-in stylesheet optimized for recitation, scripture, and reading aloud. It features large 22px typography, a generous 1.9 line-height, and a warm parchment palette to reduce eye strain.

## Usage

Link either the Georgia or Gelasio version in your `<head>`:

```html
<!-- Georgia (Native) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ceiling-lizard/warm.css@main/georgia.css">

<!-- Gelasio (Web Font) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/ceiling-lizard/warm.css@main/gelasio.css">
```

## Styling Verses

Use the included classes to format recited lines and active highlights:

```html
<div class="verse" data-current>
  <span class="verse-num">1</span> In the beginning...
  <span class="translation">Translation goes here.</span>
</div>
```

- .verse: Standard block for lines or verses.
- data-current: Highlights the active verse.
- .translation: Smaller, subordinate text for translations.
- .translit: Italicized text for transliterations.
- .verse-num: Small, superscripted verse numbers.

## Dark Mode

Automatically switches to a warm near-black (#16150F) and dimmed cream text when the device prefers a dark color scheme.
