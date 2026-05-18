# 4chan Mobile Browser

A lightweight, single-file, read-only 4chan browser optimized for mobile devices.

![4chan Mobile](https://user7210unix.github.io/mochan/)

## Features

- **Clean mobile-first UI** with bottom navigation
- **Catalog & List views** for boards
- **Thread viewer** with inline image expansion
- **Quote previews** on hover
- **Multiple themes** (Futaba, Dark, Yotsuba, Tomorrow)
- **Image proxy support** (bypasses CORS)
- **Settings** (font size, auto-load images, compact mode, etc.)
- **Search** threads and boards
- **Hide posts** with optional stubs
- Fully functional without installation — just open the HTML file

## How to Use

1. Download `index.html`
2. Open it in your browser (Chrome/Firefox recommended)
3. Browse boards, open threads, view images
4. Use the sidebar (☰) for settings and quick boards

> **Note**: This is a client-side only app that uses public proxies to fetch data from 4chan.

## Technical Details

- Pure HTML + CSS + vanilla JavaScript (no build tools)
- Uses 4chan's JSON API (`a.4cdn.org`)
- Multiple CORS proxies as fallback
- Lazy image loading
- LocalStorage for preferences
- History API support (back/forward navigation)

## Limitations

- Read-only (cannot post)
- Depends on third-party proxies (may occasionally be slow or unavailable)
- Not affiliated with 4chan.org
