# /brag Plan: KŌVÉRA

## Step 1: 9-Question Planning Rubric

1. **What is the app?**
   **KŌVÉRA** is an artisan luxury coffee & bakery mobile application built with Flutter and Firebase, offering bespoke brew customization, seasonal collections, and pickup/delivery ordering.

2. **What is the funniest or most impressive claim?**
   *"Welcome to KŌVÉRA, your sanctuary for premium coffee moments."* — Paired with *"Slow Mornings deserves best coffee"* and 12-minute artisan barista preparation.

3. **What is the visual hook?**
   The Deep Espresso (`#201613`), Burnt Caramel (`#C47A45`), and Warm Porcelain (`#F6F0E7`) luxury roastery palette ("KŌVÉRA after sunset" dark background `#15100E`), paired with Playfair Display editorial serif headings and Plus Jakarta Sans UI typography.

4. **What should be shown from the actual UI?**
   Real recorded mobile app footage showing:
   - Splash to Home screen reveal ("What will you sip today?", "THE MORNING EDIT — Caramel Cloud Latte 10% OFF")
   - Browsing "Our Specialties" across Coffee, Tea, Cookie, and Cake categories
   - Customizing a **Vanilla Cold Brew** (Size: Medium 12 oz, Sweetness: Extra Sweet, Ice: Normal Ice) & **Pistachio Cream Slice**
   - Exploring **Seasonal Editions / Curated Collections** ("Autumn Vibes — Warm & Cozy")
   - Seamless Checkout with Barista Tip & instant **"Order Confirmed!"** modal

5. **What is the shortest satisfying video?**
   20 seconds (600 frames at 30fps) in vertical `9:16` (`1080x1920`).

6. **What tone fits best?**
   - **Tone preset:** `polished`
   - **Creative direction:** Warm artisan roastery product film ("KŌVÉRA after sunset" dark espresso stage showcasing the warm porcelain & latte mist app UI).

7. **What should the audio feel like?**
   Steady, refined background track (`happy-beats-business-moves-vol-12-by-ende-dot-app.mp3`) with subtle UI interaction SFX (`switch_001.ogg`, `click_002.ogg`, `drop_001.ogg`, `impactBell_heavy_000.ogg`) timed to scene transitions and the Order Confirmed payoff.

8. **What should the share caption say?**
   Introducing KŌVÉRA: your sanctuary for premium coffee moments, bespoke brew customization, and artisan bakery ordering. Crafted with Flutter & Firebase.

9. **What's the user flow worth showing?**
   Morning sanctuary entry → Browse & customize craft brews/pastries → Seasonal discovery → 1-tap Checkout & "Order Confirmed!" in ~12 mins.

---

## Visual Identity (Extracted from `lib/core/themes/colors.dart`)

- **Dark Stage Background:** `#15100E` (`AppColors.darkBackground`) & `#201613` (`AppColors.deepEspresso`)
- **Roasted Cocoa Surface:** `#3A2721` (`AppColors.roastedCocoa`)
- **Primary Brand Accent:** `#C47A45` (`AppColors.burntCaramel`)
- **Secondary Warm Highlight:** `#D99A63` (`AppColors.softAmber`)
- **Light UI Surfaces:** `#F6F0E7` (`AppColors.warmPorcelain`) & `#EDE2D5` (`AppColors.latteMist`)
- **Muted Text:** `#B8A79D` (`AppColors.lightTextSecondary`)
- **Display Font:** `'Playfair Display', Georgia, serif`
- **Body Font:** `'Plus Jakarta Sans', -apple-system, BlinkMacSystemFont, sans-serif`

---

## Music Cue Guidance (`happy-beats-business-moves-vol-12-by-ende-dot-app.mp3`)

- **Tempo:** ~110 BPM
- **Beat Grid:** `0.56, 1.09, 1.64, 2.19, 2.73, 3.27, 3.82, 4.39, 4.91, 5.34, 6.00, 6.56, 7.09, 7.64, 8.19, 8.74, 9.29, 9.83, 10.37, 10.93, 11.46, 12.02, 12.55, 13.11, 13.64, 14.20, 14.73, 15.29, 15.84, 16.38, 16.93, 17.47, 18.02, 18.56, 19.10, 19.66s`
- **Strong Cues Locked:**
  - `4.39s` — Scene 2 transition (Our Specialties & Bakeries)
  - `8.74s` — Scene 3 transition (Bespoke Brew Customization)
  - `13.11s` — Scene 4 transition (Explore & Order Confirmed)
  - `17.47s` — Scene 5 Outro Brand Lock reveal
  - `18.02s, 18.56s, 19.10s` — Sequential pillar cards snap to the beat grid

---

## Beat-by-Beat Storyboard (20.0s Total, 9:16 Vertical `1080x1920`)

### Scene 1 (0.0s – 4.39s): Sanctuary for Coffee Moments
- **On Screen:** KŌVÉRA brand header + live phone showcase transitioning from the KŌVÉRA splash screen ("Crafted for your moment.") into the Home Screen ("What will you sip today?", "THE MORNING EDIT — Caramel Cloud Latte 10% OFF").
- **Stage Copy:**
  - Eyebrow: `☕ ARTISANAL ROASTS`
  - Headline: `What Will You Sip Today?`
  - Subline: `Your sanctuary for premium coffee moments & morning edits.`
- **Floating Pill:** `✨ Caramel Cloud Latte • 10% OFF`
- **SFX:** `drop_001.ogg` at `0.2s`

### Scene 2 (4.39s – 8.74s): Specialties & Freshly Baked Treats
- **On Screen:** Live phone footage browsing "Our Specialties" across Coffee, Tea, Cookie, and Cake categories, opening **Pistachio Cream Slice** and selecting pound weight & eggless options.
- **Stage Copy:**
  - Eyebrow: `🥐 OUR SPECIALTIES`
  - Headline: `Crafted Brews & Artisan Bakery`
  - Subline: `Single-origin coffee, ceremonial matcha, cookies & cakes.`
- **Floating Pill:** `🍰 Pistachio Cream Slice • ★ 4.8`
- **SFX:** `switch_001.ogg` at `4.39s`

### Scene 3 (8.74s – 13.11s): Bespoke Brew Customization
- **On Screen:** Live phone footage on **Vanilla Cold Brew** ("Slow-steeped over 18 hours with vanilla"), selecting Medium 12 oz, Extra Sweet, Normal Ice, and adding to order (`$5.29`).
- **Stage Copy:**
  - Eyebrow: `✨ TAILORED TO YOUR PALATE`
  - Headline: `Bespoke Brew Customization`
  - Subline: `Dial in your cup size, sweetness level, and ice preference.`
- **Floating Pill:** `🧊 18-Hour Slow-Steeped Cold Brew`
- **SFX:** `click_002.ogg` at `8.74s`

### Scene 4 (13.11s – 17.47s): Curated Discovery & Instant Checkout
- **On Screen:** Live phone footage of **Explore KOVERA** ("Seasonal Editions — Curated Collections: Autumn Vibes") transitioning into **Checkout** (`Pay $27.56`) and the **"Order Confirmed! Your barista is preparing your artisan brew. It will be ready in ~12 mins."** dialog.
- **Stage Copy:**
  - Eyebrow: `⚡ SEAMLESS ORDERING`
  - Headline: `Fast Pickup & Artisan Delivery`
  - Subline: `Fresh and ready in ~12 mins right at your door or table.`
- **Floating Pill:** `✔ Order Confirmed • Ready in ~12 mins`
- **SFX:** `click_002.ogg` at `13.11s`, `impactBell_heavy_000.ogg` at `15.29s` (when Order Confirmed appears)

### Scene 5 (17.47s – 20.0s): Outro Brand Lock
- **On Screen:** Full-screen luxury espresso & burnt caramel brand lockup with the KŌVÉRA emblem (`assets/icon/app_icon.png`), `"K Ō V É R A"`, tagline `"Crafted for your moment."`, and 3 feature pillars snapping on the beat grid (`18.02s`, `18.56s`, `19.10s`):
  1. `Single-Origin Specialty Coffee & Tea`
  2. `Handcrafted Cakes & Cookies Baked Daily`
  3. `Fast Store Pickup & Artisan Delivery`
- **Footer:** `Crafted with Flutter & Firebase`
- **SFX:** `drop_001.ogg` at `17.47s`

