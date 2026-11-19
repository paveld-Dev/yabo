================================================================================
YABO · Restaurant & Cafe Responsive HTML Email Template
Envato ThemeForest Distribution Package — Version 1.0.0
================================================================================

Thank you for purchasing YABO!

YABO is a contemporary editorial luxury email template designed for artisan
bakeries, culinary cafes, farm-to-table restaurants, specialty coffee roasters,
and lifestyle hospitality brands.

--------------------------------------------------------------------------------
1. DIRECTORY STRUCTURE
--------------------------------------------------------------------------------

YABO-Email-Template/
├── HTML/
│   └── index.html              Production HTML email template (relative image paths)
├── Images/
│   ├── hero.jpg                Overhead culinary flatlay banner (800x447)
│   ├── delivery.jpg            Kraft bag packaging lifestyle photo (600x448)
│   ├── dishes/
│   │   ├── sesame-power-bowl.jpg    Chef's favourite spotlight (480x480)
│   │   ├── dish-avocado-tomato.jpg  Signature dish 1 (260x260)
│   │   ├── dish-sunny-egg.jpg       Signature dish 2 (260x260)
│   │   ├── dish-wild-mushroom.jpg   Signature dish 3 (260x260)
│   │   └── dish-smoked-salmon.jpg   Signature dish 4 (260x260)
│   └── icons/
│       ├── logo.png, logo.svg                  Header logo (@2x Retina PNG + SVG)
│       ├── footer-logo.png, footer-logo.svg    Footer logo (@2x Retina PNG + SVG)
│       ├── instagram.png, instagram.svg        Social icon (@2x Retina PNG + SVG)
│       ├── facebook.png, facebook.svg          Social icon (@2x Retina PNG + SVG)
│       └── pinterest.png, pinterest.svg        Social icon (@2x Retina PNG + SVG)
├── Documentation/
│   └── index.html              Complete interactive HTML documentation & guide
├── ASSET-LICENSING.txt         Asset licensing & third-party rights manifest
└── README.txt                  This quick start file

--------------------------------------------------------------------------------
2. QUICK START (3 STEPS TO SEND)
--------------------------------------------------------------------------------

STEP 1: HOST YOUR IMAGES ON AN HTTPS SERVER / CDN
  Email clients (Gmail, Outlook, Apple Mail) cannot access local computer paths.
  Upload the 'Images/' folder to your web server, CDN, or ESP media library.
  In 'HTML/index.html', do a Find & Replace:
    Find:         ../Images/
    Replace with: https://yourdomain.com/path-to-images/

STEP 2: CUSTOMIZE CONTENT
  Open 'HTML/index.html' in any text editor.
  All editable sections feature unique 'mc:edit' tags:
    - hero_title, hero_subtitle, hero_button
    - dish1_title through dish4_title
    - deliv_title, deliv_body, deliv_btn
  Replace placeholder links (https://example.com/...) with your live URLs.

STEP 3: TEST & BROADCAST
  Upload to your email service provider (Mailchimp, Klaviyo, Campaign Monitor,
  SendGrid, etc.) or send a test email to your inbox across desktop and mobile.

--------------------------------------------------------------------------------
3. RENDERING ARCHITECTURE & COMPATIBILITY
--------------------------------------------------------------------------------
A. CODE-LEVEL COMPATIBILITY BUILT-IN (VERIFIED IN TEMPLATE CODE):
  * Rigid 600px table grid with Microsoft Outlook MSO conditional width locks
    (<!--[if (gte mso 9)|(IE)]>) targeting Outlook 2016, 2019, 2021 & Office 365.
  * Outlook web font defense rules automatically substitute Georgia (for serifs)
    and Arial (for sans-serifs), preventing unwanted Times New Roman substitution.
  * Bulletproof table buttons with solid hex background colors and inline padding.
  * Transparent @2x Retina PNG icons preventing SVG rendering failures in Outlook
    and Gmail mobile apps.
  * Fluid hybrid responsive media queries for screens <= 600px (320px, 375px, 414px).
  * Production HTML file size is ~44 KB (well below Gmail's 102 KB clipping limit).

B. LOCAL TEST EVIDENCE:
  * Tested in Chromium and WebKit rendering engines across viewports: 320px, 375px,
    414px, 600px, 800px, and 1200px.
  * W3C HTML validation checks passed; zero broken asset paths.

C. RECOMMENDED PRE-BROADCAST TESTING:
  * While engineered to standard email specifications, live inbox testing on
    physical Windows Outlook desktop clients with 125%/150% DPI scaling and live
    ESP campaigns (e.g., via Litmus or Email on Acid) has not been performed on
    this offline file and should be conducted prior to commercial sending.

--------------------------------------------------------------------------------
4. PLATFORM INTEGRATION NOTES
--------------------------------------------------------------------------------
* Mailchimp:
  Upload 'HTML/index.html' via Mailchimp's Classic Template Editor ("Code Your Own").
  Includes 35 unique 'mc:edit' tags and 8 'mc:repeatable' sections for visual
  text editing and section reordering.
  Pre-configured merge tags: *|UNSUB|*, *|UPDATE_PROFILE|*, *|CURRENT_YEAR|*.
  Note: Mailchimp's New Email Builder uses a closed format; use the Classic Builder.

* Klaviyo / Campaign Monitor / SendGrid:
  Import as custom HTML. Remember to update the unsubscribe merge tag:
  - Klaviyo:          {% unsubscribe %}
  - Campaign Monitor: <unsubscribe>Unsubscribe</unsubscribe>
  - SendGrid:         {{{unsubscribe}}}

--------------------------------------------------------------------------------
5. COLOR PALETTE (HEX)
--------------------------------------------------------------------------------
  * Sage Green (Primary): #5D7A68
  * Meadow Cream:         #FAF8F5
  * Pale Canvas:          #EBF0EC
  * Forest Charcoal:      #1C2620
  * Pastel Sage:          #DCE6DE
  * Warm Pine:            #688574

--------------------------------------------------------------------------------
6. TYPOGRAPHY
--------------------------------------------------------------------------------
  * Headings & Serifs: Cormorant Garamond (Georgia fallback for Outlook)
  * Body & UI Elements: Geist (System sans-serif fallback)

--------------------------------------------------------------------------------
7. ASSET LICENSING & SUPPORT
--------------------------------------------------------------------------------
Please review 'ASSET-LICENSING.txt' and 'Documentation/index.html' for full
licensing disclosures, demonstration image notices, and support instructions.

Support inquiries can be submitted via our ThemeForest author profile.

(c) 2026 YABO Kitchen & Bakery. All rights reserved.
================================================================================
