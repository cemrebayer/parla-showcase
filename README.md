# Parl'a Cafe

Parl'a is a warm, neighbourhood café concept based in Bahçeşehir, İstanbul. I created its website to feel like an extension of the space itself: welcoming, a little nostalgic and easy to spend time in.

🌐 **[Visit the live website](https://parlacoffee.com)**

## About the work

The starting point was a simple idea: a café website should not feel like a generic restaurant template. I built Parla around soft cream tones, deep burgundy details, expressive typography and warm photography to give it a more personal, editorial feeling.

The experience is designed to work just as comfortably on a phone as it does on a larger screen. It also switches between Turkish and English according to the visitor's device language.

## What I worked on

### Brand and visual direction

- Turned the café's visual references into a web identity instead of copying a single image or template.
- Built the colour system around cream, deep burgundy and soft warm-gold accents.
- Selected the typography, spacing, editorial image treatments and subtle motion to make the site feel warm and considered.
- Prepared and integrated the Parl'a logo in different versions for the hero area and the scrolling navigation state.

### Website design and front-end build

- Designed and built the full responsive experience in React, from the hero section through the story, atmosphere and footer sections.
- Created a mobile navigation experience instead of simply shrinking the desktop navigation.
- Added scroll-based header behaviour, gentle section reveals and hover states while keeping motion lightweight.
- Adjusted layouts, type scale, buttons and spacing specifically for mobile, tablet and desktop screens.
- Added Turkish and English content that follows the visitor's device language.

### Menu and management foundation

- Built a dedicated `/menu` route, ready to be used from a QR code.
- Set up a separate `/yonetim` area for managing the menu without editing the codebase.
- Created product management flows for adding, editing, hiding, republishing and permanently removing menu items.
- Added price validation that accepts Turkish decimal formatting, plus categories, dietary tags, milk-option fields and product images.
- Temporarily switched the public menu to a “We’re brewing something beautiful” screen while keeping the management structure in place for launch.

### Data, access and deployment

- Connected the menu structure to Supabase so menu changes can be stored outside the front-end code.
- Added database access rules so visitors can only read public menu items and management actions require an authorised account.
- Set up passwordless email-link login for the management area.
- Connected the project to Vercel for automatic deployments from GitHub.
- Connected the custom `parlacoffee.com` domain through GoDaddy, configured DNS records and verified HTTPS.

## Built with

React · Vite · JavaScript · CSS · Supabase · Vercel

---

This is a project showcase. The production source code is kept private.
