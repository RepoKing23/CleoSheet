# SEO Roadmap changelog

## 2026-11-24 (sixth update): This week's website fixes completed

**Checked on the live site on Nov 24, then marked Done:**
- **#156** www / non-www and canonical fix
- **#158** real internal links: 0 "#" links left, 46 internal links on the homepage
- **#192** alt text on every image
- **#193** readable text on the social icon links

**New tasks, logged as Done:**
- #196 footer "Google reviews" link
- #197 aggregateRating and review schema
- #198 alternateName schema
- #199 visible "5.0 on Google · 14 reviews" rating
- #200 build and QA: 29 pages build, navigation tests pass

**Other tabs:** Priority Issues now lists internal links, alt text and icon text as RESOLVED, so no P0 issues remain. Start Here, the 90-Day Overview (W15), Focus Targets and Metrics are updated to match.

**Still open this week:** #157 sitemap resubmit, #177 postal code revert, #182 lip filler blog, #194 Burlington meta description.

## 2026-11-24 (fifth update): Blog briefs and keyword ownership

**New tab: Blog Briefs.** 22 briefs: 15 scheduled through Feb 14, and 7 for next quarter. Each brief has:
- H1, URL slug, SEO title tag (max 60 characters) and meta description (max 155)
- one primary keyword and the supporting keywords, with DataForSEO volumes
- intent, angle and opening, H2 outline, FAQ block
- the internal link (page and anchor text)
- a "do not target" list, word count and compliance notes

**Keyword ownership map** (bottom of the Blog Briefs tab): 113 keywords, each owned by exactly one blog or service page. The build script refuses to save if any keyword is assigned twice, or if a blog targets a term a page owns.

**Overlaps fixed:**
- **#3 med spa post:** its keyword is now "how to choose a med spa," with no "Oakville" in the title or H1, because "med spa oakville" belongs to the homepage. Task #142 was renamed to match.
- **#22 (double chin)** is merged into #16 (fat-dissolving injections).
- **#21:** its primary keyword is now "lip filler migration" (720 searches a month) instead of "lip filler dissolve" (480).
- **#5** now covers cheeks, chin and jawline only, so it doesn't compete with the lip (#18) and under-eye (#13) posts.
- **Target Keywords:** "how often should you get botox" is folded into #1. The national blog keywords now point to the blog URLs in the briefs.

## 2026-11-24 (fourth update): Monitoring dates and second SE Ranking audit

**Focus Targets:** every row now has a "Monitor in" column, a "Target date to complete" column (the due date of the last linked task), and a "Target position by 14 Feb" for keywords. A "How we monitor" note was added.

**Second SE Ranking audit (24 Nov, 04:19):** health score 84 → 91, and all 25 pages are now indexable.
- **#156, the canonical fix, is Done.** Verified on the live site: www redirects (308) to non-www, and the canonical tag and sitemap both use non-www.
- **#158, real menu links, moved to this week (Nov 29).** New error "No inbound links" on all 25 pages. The live homepage has 40 `href="#"` links that only work through JavaScript.
- **New tasks due Nov 29:**
  - #192 alt text on 13 pages
  - #193 text for the icon-only links
  - #194 shorter meta description on the Burlington page
- **#195:** re-run the audit on Dec 6.
- **Updated tabs:** Priority Issues, Start Here, 90-Day Overview (W15), Metrics and Focus Targets.

## 2026-11-24 (third update): Focus targets and competitor pages

**New tab: Focus Targets.** It has three sections:
1. Keywords gaining position. This comes from SE Ranking daily positions, Nov 13–24. Each keyword has a focus level, a recommended action and its task IDs.
2. New competitor pages to copy or compete with. This comes from the SE Ranking new-competitor-pages export. Each page has our planned response, task IDs and a due date. Services Cleo doesn't offer, and pricing pages, are marked "Skip".
3. Page fixes, listed in the order to do them.

**New tasks:**
- #182 lip filler blog (Nov 29)
- #183 lip filler page
- #184 nurse injector /about
- #185 fat dissolving page
- #186 skin boosters page
- #187 Google profile fixes
- #188 concern pages
- #189 Botox page
- #190 natural lip filler blog
- #191 0.5 vs 1 ml lip filler blog

**Blog schedule now:** 1 in Nov, 5 in Dec, 5 in Jan, 4 by Feb 14.
- #175 (NP vs nurse vs doctor) moved to Dec 13, because "nurse injector oakville" is climbing fast.
- #110 (Is Botox safe) moved to Feb 14.

**Blogs tab:** 6 posts added: lip filler duration, natural lip filler, 0.5 vs 1 ml, lip filler dissolving, double chin injections, Botox for forehead lines. The lip swelling post was merged into "aftercare and swelling," and the skin boosters post now includes before-and-afters.

## 2026-11-24 (second update): Sheet-wide sync, postal code fix, heatmap monitor

**Postal code:** L6M 4L9 is correct (confirmed by the user, and it matches the Google profile).
- Fixed on Start Here, Local Citations ("THE RECORD"), Citations and the 90-Day Overview.
- Tasks #42–#44 had changed Apple Maps, Bing and RateMDs to L6M 0T9 in September. New task #177 changes them back, and #178 re-checks every listing.
- Task #53 now says L6M 4L9.

**Website:** changed to https://luxurybeautyaesthetic.com on Start Here and Local Citations, to match the Google profile and the live site.

**Start Here**
- The "Right now" timeline now shows Nov, Dec, Jan and Feb.
- The keyword and data notes are updated.
- Pointers to the Priority Issues and Heatmap Monitor tabs were added.

**90-Day Overview:** new "week by week — the second half" section for W14–W26. Its counts pull live from the Tasks tab. The Month 4–6 themes were rewritten.

**Metrics:** end-of-November numbers added:
- pages indexed: 9
- site health score: 84
- referring domains: 0
- a blog post counter

**New tab: Heatmap Monitor**
- A 5×5 Google Maps grid with points 1.5 km apart, centred on the Google listing (43.476, -79.736).
- Five priority keywords, ranked from DataForSEO volumes, SE Ranking positions and the map ranks on the Metrics tab.
- Grid coordinates, colour-coded entry grids for Dec, Jan and Feb, and automatic average-rank and top-3 share.

**Tasks:** #179 heatmap baseline (6 Dec), #180 re-run (3 Jan), #181 re-run (7 Feb).

**Priority Issues:** added the postal code issue as P1.

## 2026-11-24: Revision from SE Ranking audit and insights

Sources: the SE Ranking website audit, keyword cannibalisation, poor-quality content, new competitor pages and positions exports (24 Nov), checked with DataForSEO.

**New tab: Priority Issues.** Nine issues ranked P0 to P3, each with its evidence, fix, task IDs and due date.

**Tasks tab**
- Critical fix added for the week of 29 Nov: #156, the www / non-www canonical conflict (0 of 50 pages indexable), and #157, resubmitting the sitemap.
- Removed under the rule of no graphic or social media tasks through February:
  - #114 Instagram review
  - #115 GBP photo refresh
  - #128 holiday Instagram plan
  - #130 gift-card ad creative
  - #133 holiday Instagram cadence
  - #138 Instagram back to full cadence
- Blogs now run at 3–5 a month: 4 in December, 5 in January and 3 by 14 Feb.
  - The generic "write the Nth article" tasks were turned into specific posts.
  - Overdue November slots (#105, #110, #113, #119) were moved into December–February.
  - New blog tasks are #172–176.
- New technical and on-page tasks:
  - #158 crawlable internal links
  - #159 post-fix baseline
  - #160 cannibalisation fix
  - #162 expand /locations, /faq and /about
  - #163 rewrite the Burlington, Milton and Mississauga pages
  - #170 compliance pass
- New location pages:
  - #166 Hamilton
  - #167 Brampton
  - #168 Etobicoke
  - #169 Georgetown
- Existing task wording updated: #136, #137, #151.
- Owners on existing tasks were left unchanged. Every new task is assigned to Agency only.

**Blogs tab**
- Added two columns: "Monthly searches (CA)" and "Scheduled (Tasks tab)".
- Added 7 posts:
  - masseter Botox
  - lip flip
  - under-eye filler
  - jawline filler
  - skin boosters
  - fat-dissolving injections
  - Botox for sweating
- Pricing posts were skipped, following the no-pricing rule.

**Target Keywords tab**
- Added 11 location keywords: Hamilton, Ancaster, Brampton, Etobicoke, Georgetown, med spa mississauga, and Guelph as watch-only.
- Filled in search volume (DataForSEO, Canada) and the current position (SE Ranking, 24 Nov) where available.
