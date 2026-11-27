# Yuke® Portfolio — Asset Preparation Guide

This guide was generated from the current `index.html` and matches it. **You do not need to edit any code.** Upload each file with the **exact name** shown, into the **exact folder**, and it appears on its page automatically. A slot with no file keeps showing its grey placeholder, so you can add assets gradually. No filenames or folders were renamed or moved in the latest update.

## 1. Quick summary

| Volume | Existing slots | **Required** | Optional | Videos | Folder |
|---|---|---|---|---|---|
| VOL. 01 — Social Media | 20 | **6** | 14 | 2 | `images/social-media/` |
| VOL. 02 — Beyond Numbers | 0 | **0** | 0 | 0 | `images/paid-media/` (no uploads) |
| VOL. 03 — Creative Works | 16 | **5** | 11 | 0 | `images/creative/` |
| VOL. 04 — Brand Stories | 16 | **5** | 11 | 2 | `images/brand-stories/` |
| **Total** | **52** | **16** | 36 | 4 | |

**What "Required" means.** The website loads with zero uploads. "Required" is the minimum for a chapter to look finished: one opener image per chapter (slot 1), because the opener page has no other visual. Everything else (gallery images, videos, covers, spreads) is **optional**. Add them only when the work is strong.

## 2. File rules (all volumes)

| Rule | Detail |
|---|---|
| Folders | `images/social-media/`, `images/paid-media/`, `images/creative/`, `images/brand-stories/` (create in GitHub: **Add file → Create new file**, type `images/social-media/readme.txt`, commit; repeat). |
| Names | Lowercase, hyphens, no spaces. Case matters on GitHub Pages. |
| Image format | **JPG** preferred (quality about 85). PNG or WebP also work with the same base name (`.png` / `.webp`); the site tries jpg, png, then webp. |
| Image pixels and size | Long edge **1600 px**, **under 400 KB** each. Screenshots: capture at full size, then export at 1600 px. |
| Double-page spreads | JPG, **3:2, 2400 × 1600 px, under 700 KB**. |
| Video | **MP4 (H.264)** only for the named video slots, **under 25 MB** (GitHub's browser upload limit), 1080p max, about 30–60 seconds. Vertical 9:16 = 1080 × 1920; horizontal 16:9 = 1920 × 1080. |
| Video cover (optional) | Same name as the video plus `-poster.jpg` (e.g. `tiktok-2.mp4` → `tiktok-2-poster.jpg`), JPG under 400 KB, same ratio as the video. Without it the browser shows the first frame. |
| Cropping | Nothing is ever cropped. Any ratio works; the ratio columns show the shape each slot is designed for. |
| Privacy | Blur client names, budgets, emails and anything confidential. Only show results you can verify. |

**Recommended pixels by ratio** (long edge 1600): square 1:1 = 1600 × 1600 · landscape 3:2 = 1600 × 1067 · landscape 16:9 = 1600 × 900 · portrait 4:5 = 1280 × 1600 · portrait 9:16 = 900 × 1600.

## 3. How the pages use your images

Each chapter is four pages (six if it has a spread):

1. **Opener (left page)**: slot 1, in a landscape-ish area (about 440 × 300 px on desktop). **Landscape or square images look best**; tall images appear small.
2. **Overview (right page)**: text only.
3. **Gallery (left page)**: slots 2 and 3. Chapters 1, 3, 5 of each volume show them **side by side** (portrait-friendly); chapters 2, 4, 6 show them **stacked** (landscape-friendly).
4. **Strategy page (right page)**: text only.
5. **Spread (optional, 2 pages)**: one image across both pages.

**VOL. 02 is different** (see below): it has no image slots.

Not image slots: the four covers, the carousel, About and Contact (all made in code).

## VOL. 01 — SOCIAL MEDIA

Folder: `images/social-media/`

**Existing slots: 20** (16 images, 2 videos, 2 double-page spreads). **Required: 6** (the opener image of each chapter). **Optional: 14**.

| File name | Slot | Page | Aspect ratio | Pixels | Max size | Format | Status | What to prepare |
|---|---|---|---|---|---|---|---|---|
| `x-twitter-1.jpg` | **X (Twitter)** — Account screenshot | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Profile page: banner, handle and follower count. Add a growth or analytics screenshot into the same image if you want both. |
| `x-twitter-2.jpg` | **X (Twitter)** — Content example | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | One strong post, screenshot including likes / views. |
| `x-twitter-3.jpg` | **X (Twitter)** — Campaign visual | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | A campaign graphic or thread cover you published on X. |
| `x-twitter-spread.jpg` | **X (Twitter)** — double-page feature | Spread (both pages) | 3:2 | 2400 × 1600 | ≤ 700 KB | JPG | Optional | Wide hero: collage of your best X posts or one campaign key visual. |
| `facebook-1.jpg` | **Facebook** — Account screenshot | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Page home with followers / likes visible (or Insights growth chart). |
| `facebook-2.jpg` | **Facebook** — Content example | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Representative post screenshot. |
| `facebook-3.jpg` | **Facebook** — Campaign visual | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Campaign creative used on the Page. |
| `tiktok-1.jpg` | **TikTok** — Account screenshot | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Profile with follower count (or analytics overview). |
| `tiktok-2.mp4` | **TikTok** — Video example | Gallery, side by side | Video 9:16 | 1080 × 1920 | ≤ 25 MB | MP4 (H.264) | Optional | Your best-performing video. MP4, vertical 9:16. Optional cover: `tiktok-2-poster.jpg` (JPG, same ratio, under 400 KB). |
| `tiktok-3.jpg` | **TikTok** — Campaign visual | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Campaign creative or a video cover frame. Use a vertical or square image (it sits next to a vertical video). |
| `instagram-1.jpg` | **Instagram** — Account screenshot | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Profile grid screenshot, or Insights growth screenshot. |
| `instagram-2.jpg` | **Instagram** — Content example | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Representative post or Reel cover. |
| `instagram-3.jpg` | **Instagram** — Campaign visual | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Campaign visual. |
| `instagram-spread.jpg` | **Instagram** — double-page feature | Spread (both pages) | 3:2 | 2400 × 1600 | ≤ 700 KB | JPG | Optional | Wide hero: grid mosaic or campaign key visual. |
| `linkedin-1.jpg` | **LinkedIn** — Account screenshot | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Page / profile screenshot with followers or analytics. |
| `linkedin-2.jpg` | **LinkedIn** — Content example | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Top post screenshot. |
| `linkedin-3.jpg` | **LinkedIn** — Campaign visual | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Campaign or thought-leadership graphic. |
| `youtube-1.jpg` | **YouTube** — Channel screenshot | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Channel home with subscribers, or YouTube Studio analytics. |
| `youtube-2.mp4` | **YouTube** — Video example | Gallery, stacked | Video 16:9 | 1920 × 1080 | ≤ 25 MB | MP4 (H.264) | Optional | Featured video, MP4 16:9, ideally under 25 MB. Optional cover: `youtube-2-poster.jpg` (JPG, same ratio, under 400 KB). |
| `youtube-3.jpg` | **YouTube** — Thumbnail / campaign visual | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Thumbnail collection or campaign visual. |

## VOL. 02 — BEYOND NUMBERS

Folder: `images/paid-media/` (kept; **no uploads needed**). Existing slots: **0**. Required: **0**.

Real advertising screenshots, dashboards, budgets and client reports cannot be published, so every Vol. 02 visual is drawn **in the website code**. None looks like a real dashboard. **Rule: one main visual per platform chapter.**

| # | Chapter | Subtitle | Visual (made in code) | Upload? |
|---|---|---|---|---|
| 01 | **Meta Ads** | App Campaigns · Account Setup · Campaign Testing | One conceptual Meta app-advertising illustration (opener) | No |
| 02 | **TikTok Ads** | App Campaigns · Website Landing Pages · Creator-led Advertising | One conceptual TikTok advertising illustration (opener) | No |
| 03 | **Google Ads** | App Campaigns · Multi-category Campaigns · Performance Optimization | One conceptual Google app-advertising illustration (opener) | No |
| 04 | **Optimization & Tracking** | Data Analysis · Attribution · Tracking Setup · Campaign Optimization | One original five-step workflow infographic (opener) | No |

**Google Ads case studies (no uploaded screenshots required).** Both are typography plus a before/after cost comparison, drawn in code:

| Case | Type | Cost per conversion |
|---|---|---|
| 01 | Mobile game / card game app | USD 1.50 → Below USD 0.60 |
| 02 | E-commerce website landing page | USD 1.50 → USD 0.45 |

Conversion event, period and notes show `[Replace: confirm]` until you supply them in the `MAGS` list in `index.html`.

**Average daily spend** (Meta, TikTok, Google): each shows "Average Daily Spend: To be updated". Set `ds:` on the chapter to an approved range, or `ds:null` to hide it.

**Retired files.** These old files in `images/paid-media/` are **no longer referenced** by the site and are **not required**. They were not renamed, moved or deleted: `meta-ads-1/2/3.jpg`, `meta-ads-spread.jpg`, `tiktok-ads-1/2/3.jpg`, `media-planning-1/2/3.jpg`, `optimization-analysis-1/2/3.jpg`. If any is a real dashboard, delete it from the repo so it is not reachable by URL.

## VOL. 03 — CREATIVE WORKS

Folder: `images/creative/`

**Existing slots: 16** (15 images, 0 videos, 1 double-page spread). **Required: 5** (the opener image of each chapter). **Optional: 11**.

Positioning: marketing ideas and product information turned into effective visual content. **No video in this volume** (video lives in VOL. 04). Quality over quantity; place each piece where it best shows its purpose and do not repeat a piece across chapters.

**Old filenames are kept and mapped to the new visible chapter names:**

| Visible chapter | Focus | Filename prefix |
|---|---|---|
| 01 **Visual Design** | Strongest work: marketing visuals, key visuals, creative compositions, infographics | `graphic-design` |
| 02 **Campaign Visuals** | Exhibition campaigns, e-commerce promotions, seasonal campaigns, event posters, campaign visual systems | `campaign-posters` |
| 03 **Social Media Creatives** | Social graphics, post designs, carousels, platform-specific creatives, content series | `social-visuals` |
| 04 **Product Communication** | Product promotional visuals, feature graphics, information layouts, benefits, marketing materials | `product-materials` |
| 05 **Selected Works** | Other outstanding executions that fit none of the above (not framed as personal experiments) | `experiments-personal-projects` |

| File name | Slot | Page | Aspect ratio | Pixels | Max size | Format | Status | What to prepare |
|---|---|---|---|---|---|---|---|---|
| `graphic-design-1.jpg` | Visual Design — Featured work | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Your strongest piece, full image, uncropped. |
| `graphic-design-2.jpg` | Visual Design — Detail or variation | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Detail crop or alternate version. |
| `graphic-design-3.jpg` | Visual Design — Shown in context | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Mockup or real-life photo. |
| `graphic-design-spread.jpg` | Visual Design — double-page feature | Spread (both pages) | 3:2 | 2400 × 1600 | ≤ 700 KB | JPG | Optional | Your single best wide-format piece. |
| `campaign-posters-1.jpg` | Campaign Visuals — Campaign key visual | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Main visual of one campaign. |
| `campaign-posters-2.jpg` | Campaign Visuals — Poster or variation | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Second poster or variation. |
| `campaign-posters-3.jpg` | Campaign Visuals — Shown in context | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Poster in situ / mockup. |
| `social-visuals-1.jpg` | Social Media Creatives — Featured creative | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Carousel cover or key post graphic. |
| `social-visuals-2.jpg` | Social Media Creatives — Another from the set | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Another from the same series. |
| `social-visuals-3.jpg` | Social Media Creatives — Shown in the feed | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Feed mockup. |
| `product-materials-1.jpg` | Product Communication — Featured material | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Flyer / one-pager / feature graphic. |
| `product-materials-2.jpg` | Product Communication — Detail or close-up | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Close-up of how a feature is explained. |
| `product-materials-3.jpg` | Product Communication — In use or in print | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | In use or in print. |
| `experiments-personal-projects-1.jpg` | Selected Works — Featured work | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Your best piece that fits no other chapter. |
| `experiments-personal-projects-2.jpg` | Selected Works — Selected work | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Another selected piece. |
| `experiments-personal-projects-3.jpg` | Selected Works — Selected work | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Another selected piece. |

## VOL. 04 — BRAND STORIES

Folder: `images/brand-stories/`

**Existing slots: 16** (13 images, 2 videos, 1 double-page spread). **Required: 5** (the opener image of each chapter). **Optional: 11**.

| File name | Slot | Page | Aspect ratio | Pixels | Max size | Format | Status | What to prepare |
|---|---|---|---|---|---|---|---|---|
| `brand-storytelling-1.jpg` | **Brand Storytelling** — Key visual | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Key visual or story cover. |
| `brand-storytelling-2.jpg` | **Brand Storytelling** — Storyboard or still | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Storyboard frame or video still. |
| `brand-storytelling-3.jpg` | **Brand Storytelling** — Campaign visual | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Campaign visual. |
| `brand-storytelling-spread.jpg` | **Brand Storytelling** — double-page feature | Spread (both pages) | 3:2 | 2400 × 1600 | ≤ 700 KB | JPG | Optional | Wide hero: cinematic key frame or collage. |
| `product-videos-1.jpg` | **Product Videos** — Video still | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Cover still from the video (JPG). |
| `product-videos-2.mp4` | **Product Videos** — Video example | Gallery, stacked | Video 16:9 | 1920 × 1080 | ≤ 25 MB | MP4 (H.264) | Optional | The video. MP4 16:9, under 25 MB. Optional cover: `product-videos-2-poster.jpg` (JPG, same ratio, under 400 KB). |
| `product-videos-3.jpg` | **Product Videos** — Behind the scenes | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Behind-the-scenes photo. |
| `short-form-video-1.jpg` | **Short-form Video** — Video still | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Vertical cover still (JPG). |
| `short-form-video-2.mp4` | **Short-form Video** — Video example | Gallery, side by side | Video 9:16 | 1080 × 1920 | ≤ 25 MB | MP4 (H.264) | Optional | Vertical MP4 9:16, under 25 MB. Optional cover: `short-form-video-2-poster.jpg` (JPG, same ratio, under 400 KB). |
| `short-form-video-3.jpg` | **Short-form Video** — Campaign visual | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Campaign visual. |
| `creative-direction-1.jpg` | **Creative Direction** — Key visual | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Key visual / moodboard. |
| `creative-direction-2.jpg` | **Creative Direction** — Storyboard or still | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Storyboard or still. |
| `creative-direction-3.jpg` | **Creative Direction** — Campaign visual | Gallery, stacked | Landscape 16:9 or 3:2 | 1600 × 900 or 1600 × 1067 | ≤ 400 KB | JPG | Optional | Campaign visual. |
| `campaign-storytelling-1.jpg` | **Campaign Storytelling** — Key visual | Opener | Landscape 3:2 or square 1:1 | 1600 × 1067 or 1600 × 1600 | ≤ 400 KB | JPG | **Required** | Hero image of the campaign. |
| `campaign-storytelling-2.jpg` | **Campaign Storytelling** — Storyboard or still | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Storyboard or still. |
| `campaign-storytelling-3.jpg` | **Campaign Storytelling** — Campaign visual | Gallery, side by side | Portrait 4:5 or 9:16 | 1280 × 1600 or 900 × 1600 | ≤ 400 KB | JPG | Optional | Campaign visual. |

## 4. Known limits

- **Growth and analytics screenshots** (Vol. 01) have no dedicated slot. Put them in slot 1, or merge profile and analytics into one image.
- **Numbers and text** are typed in the `MAGS` list at the top of the script in `index.html`, not uploaded. They show `—` or `[Replace: …]` until you fill them. Homepage figures (340K+ etc.) still need a confirmed source and period.
- Changed a file but the old one shows? Hard refresh (Ctrl+F5) after GitHub Pages rebuilds (1–2 minutes).

## 5. How to upload

1. Open your repo on github.com and go into the right `images/...` folder.
2. **Add file → Upload files**, drag the correctly named files in, **Commit changes**.
3. Wait 1–2 minutes, refresh the site, open the volume and flip to the chapter.
