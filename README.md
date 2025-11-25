# 🎄 Christmas Scripts

Beautiful, lightweight JavaScript animations to bring holiday cheer to your website.

[![Website](https://img.shields.io/badge/Website-christmas--scripts.arnaullopart.com-blue)](https://christmas-scripts.arnaullopart.com/)
[![License](https://img.shields.io/badge/License-Proprietary-red)](#copyright--license)

## 🌐 Live Demo & Playground

**Visit our interactive demo:** [christmas-scripts.arnaullopart.com](https://christmas-scripts.arnaullopart.com)

The website features:
- ✨ **Live demonstrations** of all Christmas animations in action
- 🎮 **Interactive control panel** to test and customize each effect in real-time
- 📋 **Auto-generated code snippets** with your custom configurations
- 🎯 **Visual examples** showing all available parameters and options
- 📱 **Fully responsive** playground that works on all devices

Use the playground to experiment with different settings, test combinations of effects, and generate the exact script tags you need for your website!

## 📖 Table of Contents

- [Overview](#overview)
- [Quick Start](#quick-start)
- [Available Scripts](#available-scripts)
  - [Snowflakes ❄️](#snowflakes-️)
  - [Christmas Lights 💡](#christmas-lights-)
  - [Garlands 🎀](#garlands-)
  - [Santa Claus 🎅](#santa-claus-)
- [Installation](#installation)
- [Configuration](#configuration)
- [Browser Support](#browser-support)
- [Legal & Compliance](#legal--compliance)
- [Copyright & License](#copyright--license)

## Overview

Christmas Scripts is a collection of festive JavaScript animations that can be easily added to any website. Each script is:

- **Lightweight**: Minimal performance impact
- **Easy to integrate**: Just add a single script tag
- **Customizable**: Configure via URL parameters
- **Date-aware**: Automatically show/hide based on date ranges
- **Theme-aware**: Auto-detection of light/dark themes (where applicable)
- **No dependencies**: Pure vanilla JavaScript

> 💡 **Try it live!** Visit [christmas-scripts.arnaullopart.com](https://christmas-scripts.arnaullopart.com) to see all effects in action and use the interactive playground to generate custom code snippets for your website.

## Quick Start

Add any of these scripts to your HTML:

```html
<!-- Snowflakes -->
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-snowflakes.min.js?startDate=12-01&endDate=01-15"></script>

<!-- Christmas Lights -->
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-lights.min.js?startDate=12-01&endDate=01-15"></script>

<!-- Garlands -->
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-garlands.min.js?startDate=12-01&endDate=01-15"></script>

<!-- Santa Claus -->
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-santa-claus.min.js?startDate=12-01&endDate=01-15"></script>
```

## Available Scripts

### Snowflakes ❄️

Create beautiful falling snowflakes across your entire page with automatic theme detection.

**Script URL:**
```html
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-snowflakes.min.js"></script>
```

**Parameters:**

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| `startDate` | String (MM-DD) | `"12-01"` | When to start showing snowflakes |
| `endDate` | String (MM-DD) | `"01-15"` | When to stop showing snowflakes |
| `theme` | String | `auto` | Color scheme: `"light"`, `"dark"`, or null for auto-detection |

**Example:**
```html
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-snowflakes.min.js?startDate=12-01&endDate=01-15&theme=dark"></script>
```

### Christmas Lights 💡

Add colorful twinkling lights around the borders of your webpage.

**Script URL:**
```html
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-lights.min.js"></script>
```

**Parameters:**

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| `startDate` | String (MM-DD) | `"12-01"` | When to start showing lights |
| `endDate` | String (MM-DD) | `"01-15"` | When to stop showing lights |
| `theme` | String | `auto` | Color scheme: `"light"`, `"dark"`, or null for auto-detection |
| `positions` | String | `"top,right,bottom,left"` | Comma-separated border positions |

**Example:**
```html
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-lights.min.js?startDate=12-01&endDate=01-15&positions=top,bottom&theme=dark"></script>
```

### Garlands 🎀

Decorate your page with festive garlands that gently sway and breathe.

**Script URL:**
```html
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-garlands.min.js"></script>
```

**Parameters:**

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| `startDate` | String (MM-DD) | `"12-01"` | When to start showing garlands |
| `endDate` | String (MM-DD) | `"01-15"` | When to stop showing garlands |
| `positions` | String | `"top"` | Comma-separated positions: `"top"`, `"bottom"` |
| `type` | String | `"garlands"` | Decoration style: `"garlands"`, `"garlands2"`, `"garlands3"`, `"trees"`, or `"gingerbread"` |
| `fullsize` | Boolean | `false` | Set to `"true"` or `"1"` for full-width garlands |

**Example:**
```html
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-garlands.min.js?startDate=12-01&endDate=01-15&positions=top,bottom&type=garlands&fullsize=false"></script>
```

### Santa Claus 🎅

Watch Santa fly across your screen in his sleigh, spreading holiday joy!

**Script URL:**
```html
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-santa-claus.min.js"></script>
```

**Parameters:**

| Parameter | Type | Default | Description |
|-----------|------|---------|-------------|
| `startDate` | String (MM-DD) | `"12-01"` | When to start Santa's flights |
| `endDate` | String (MM-DD) | `"01-15"` | When to stop Santa's flights |
| `onlyHorizontalMovements` | Boolean | `false` | Set to `"true"` or `"1"` for horizontal-only flight |
| `audioEffectsEnabled` | Boolean | `false` | Set to `"true"` or `"1"` to enable jingle bell sounds |

**Example:**
```html
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-santa-claus.min.js?startDate=12-01&endDate=01-15&onlyHorizontalMovements=false&audioEffectsEnabled=true"></script>
```

## Installation

### CDN (Recommended)

Simply include the script tags in your HTML:

```html
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-snowflakes.min.js"></script>
```

### Multiple Effects

You can combine multiple effects on the same page:

```html
<!-- Add snowflakes and lights together -->
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-snowflakes.min.js?startDate=12-01&endDate=01-15"></script>
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-lights.min.js?startDate=12-01&endDate=01-15&positions=top,bottom"></script>
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-garlands.min.js?startDate=12-01&endDate=01-15&positions=top"></script>
<script defer src="https://christmas-scripts.arnaullopart.com/christmas-santa-claus.min.js?startDate=12-01&endDate=01-15"></script>
```

### Placement

- Add scripts before the closing `</body>` tag or in the `<head>` with the `defer` attribute
- Scripts will automatically initialize when the page loads
- No additional configuration or initialization code is required

## Configuration

### Date Format

All date parameters use the `MM-DD` format (e.g., `"12-01"` for December 1st, `"01-15"` for January 15th).

The scripts will only display effects during the specified date range. If the current date is outside the range, the effects won't be displayed.

### Theme Detection

For snowflakes and lights, the scripts can automatically detect your website's theme:

- **Auto-detection**: Leave the `theme` parameter empty or omit it
- **Manual override**: Set `theme=light` or `theme=dark`

The auto-detection analyzes the background color of your page to determine the appropriate effect colors.

### Boolean Parameters

Boolean parameters can be set using:
- `true`, `"true"`, or `"1"` for true
- `false`, `"false"`, or `"0"` for false

Examples:
```html
<!-- Enable audio -->
?audioEffectsEnabled=true

<!-- Enable fullsize garlands -->
?fullsize=1
```

## Browser Support

These scripts work in all modern browsers:

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

**Minimum Requirements:**
- ES6 JavaScript support
- CSS3 animations
- Canvas API (for snowflakes)

**Mobile Support:**
- Fully responsive
- Touch-friendly
- Optimized for performance on mobile devices

## Legal & Compliance

We take your privacy and legal rights seriously. Please review our legal documentation:

- **[Privacy Policy](https://christmas-scripts.arnaullopart.com/privacy-policy.html)** - How we collect and use information
- **[Terms of Service](https://christmas-scripts.arnaullopart.com/terms-of-service.html)** - Usage terms and conditions
- **[Cookie Policy](https://christmas-scripts.arnaullopart.com/cookie-policy.html)** - How we use cookies on our website

**Important Notes:**
- Our JavaScript libraries do NOT use cookies or track users
- The scripts run entirely client-side in the user's browser
- No personal data is collected by the scripts
- Website analytics apply only to christmas-scripts.arnaullopart.com

## Copyright & License

**Copyright © 2025 Arnau Llopart. All Rights Reserved.**

This software is licensed under a **Proprietary License**. See the [LICENSE.md](LICENSE.md) file for complete terms and conditions.

### Quick Summary

**YOU MAY:**
- ✅ Use the Software on any website or application
- ✅ Include the Software in commercial projects
- ✅ Use the Software for personal or business purposes
- ✅ Implement via the official CDN for unlimited projects

**YOU MAY NOT:**
- ❌ Copy, modify, or create derivative works of the Software
- ❌ Distribute, sublicense, or sell copies of the Software
- ❌ Host the Software on your own servers or CDNs
- ❌ Remove or alter any copyright notices or attributions

### Full License

For complete terms, conditions, warranties, and limitations of liability, please read the full [LICENSE.md](LICENSE.md) file.

For licensing inquiries or permissions beyond this license, please contact: [Arnau Llopart](https://www.linkedin.com/in/arnau-llopart-58589916b/)

---

## 🎁 Author

**Arnau Llopart**

- Website: [christmas-scripts.arnaullopart.com](https://christmas-scripts.arnaullopart.com)
- GitHub: [@arnaullfe](https://github.com/arnaullfe)
- LinkedIn: [arnau-llopart](https://www.linkedin.com/in/arnau-llopart-58589916b/)
- Instagram: [@arnau_llopart](https://www.instagram.com/arnau_llopart/)
- YouTube: [@ArnauLlopart](https://www.youtube.com/@ArnauLlopart)
- X (Twitter): [@arnaullfe](https://x.com/arnaullfe)

---

Made with ❤️ and holiday spirit by Arnau Llopart • Enjoy the festive season! 🎄

