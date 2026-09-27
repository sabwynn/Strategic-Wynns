# Strategic Wynns LLC: Website (v2.4)

Static site: no frameworks, no build step. Pages: `index.html`, `services.html`,
`about.html`, `contact.html`, plus `assets/`, `robots.txt`, `sitemap.xml`.

## Preview locally
Double-click `index.html`, or run `python -m http.server` here and open http://localhost:8000

## v2.4 changelog: Paonia funding record corrected (per Stefen, first person)
- The Paonia funding record now covers WATER only. The June 2025 press report
  described the roughly $11 million as covering water and wastewater projects
  together; Stefen confirms wastewater was not part of it. Both affected sentences
  (the close of the opening paragraph and the funding-record paragraph) now say
  water only. Verified: zero wastewater mentions remain on the About page.

## v2.3 changelog: Paonia bio corrected and independently verified; ICMA review
1. **Natural opening.** The old meta opening (announcing which example follows) is
   gone. The biography now opens directly with the work so a first-time reader sees
   the accomplishment.
2. **Press-verified numbers replace the earlier figures.** Independent sources now
   back every claim: a $9.7 million State Revolving Fund loan for phase one with
   $3 million in principal forgiveness; roughly $11 million in grants and loans for
   water and wastewater; two WaterSMART grants from the Bureau of Reclamation; just
   under $2 million for the Fifth and Grand intersection rebuild; the first
   comprehensive plan since 1996 (started three times before) winning the APA Small
   Town and Rural Division's Vernon Deines Merit Award; and the town's first GFOA
   Distinguished Budget Presentation Awards, first in Delta County.
   Note: the earlier $6.7 million figure appears to be the $9.7 million loan minus
   $3 million principal forgiveness. Confirm with Stefen which framing he prefers
   on any future resume or proposal use.
3. **"Deferred for decades" restored**, in its accurate context: infrastructure
   deferred for decades was finally moving during his tenure (supported by press
   coverage and the town's own releases).
4. **ICMA review.** The flagged sentence ("the earlier credential-as-selling-device phrasing") was rewritten so the credential appears only as a factual
   suffix ("Stefen A.B. Wynn, M.P.A., ICMA-CM"), which is the form ICMA's own
   credentialing guidance permits on professional documents. Added a "Bound by a
   code of ethics" value card. See the ICMA section below.
5. Hero artwork unchanged (clean crop, OCR-verified, no client-specific text).

## ICMA compliance notes (for Stefen, not for the public site)
From ICMA's own pages (icma.org/page/icma-code-ethics, the credentialing pages,
and the ethics issues and advice library):
- The Code applies to all members. Members working in local government follow all
  12 Tenets. Members in the private sector (students, retirees, state/federal,
  private sector) are required to follow Tenets 1 and 3. As an independent
  consultant, Stefen is a private-sector member bound by Tenets 1 and 3.
- Consulting is explicitly contemplated: ICMA's ethics advice library states that
  members may serve as consultants or take other paid outside employment when it
  does not create a conflict (that guidance addresses members in government
  service; Stefen currently holds no public office, which removes the employer
  conflict question entirely).
- Using the credential: ICMA's credentialing FAQ states the initials or title
  (ICMA-CM) may be used after the name on letterhead, business cards, or other
  professional documents. A website bio in the form "Stefen A.B. Wynn, M.P.A.,
  ICMA-CM" is that permitted use.
- The credential must be renewed annually, and Tenet 8 carries a 40 hour annual
  professional development requirement. ACTION: confirm the credential is current
  for 2026 before launch; if it ever lapses, remove "ICMA-CM" from the site.
- What the site must never do: imply ICMA endorses the firm (it does not and the
  site does not), misrepresent his current status (he holds no public office; the
  site does not claim otherwise), or misstate the credential's status.
- Confidential check: ICMA's ethics director (Jessica Cowles, jcowles@icma.org,
  listed publicly by ICMA) offers confidential advice to members. A short email
  describing the consulting practice would give personal sign-off beyond this
  desk review.

## Independent verification sources for the Paonia record
1. Town of Paonia press release, March 11, 2026 (second WaterSMART grant, Bureau
   of Reclamation; Western Loop project; Wynn quoted):
   townofpaonia.colorado.gov/news-article/town-of-paonia-selected-for-second-watersmart-grant-to-improve-water-infrastructure
2. Town of Paonia press release, March 20, 2026 (2025 Comprehensive Plan "A
   Community Driven Framework for a Resilient Rural Future" wins APA Small Town
   and Rural Division Vernon Dienes Merit Award; "initiated three separate times
   in the past but never brought to completion"):
   townofpaonia.colorado.gov/news-article/town-of-paonia-receives-national-planning-merit-award-for-2025-comprehensive-plan
3. High Country Spotlight, March 17, 2025 ($9.7M SRF phase one loan, $3M principal
   forgiveness, $1M EIAF, GFOA award first in Delta County; moratorium effective
   January 27, 2020 following the 2019 outage):
   highcountryspotlight.com/spotlight/paonia-trustees-water-infrastructure-and-standby-taps/article_fcf35df2-034c-11f0-8ec0-4316bbe66471.html
4. High Country Spotlight, June 30, 2025 (capital projects "fully funded": about $11M for water projects and just under $2M for Fifth and Grand; the report described the $11M as water and wastewater together, which Stefen corrects to water only):
   highcountryspotlight.com/local_news/civically_engaged/paonia-capital-projects-funded-lawsuit-dismissed-fees-established-and-a-flooded-basement-mystery/article_760411f9-1273-436b-9dbf-f96943bc3af6.html
5. KVNF public radio, August 5, 2025 ("finally starting work on our water capital
   improvement plan, phase one"):
   kvnf.org/kvnf-stories/2025-08-05/water-infrastructure-series-paonia
6. Delta County Independent, August 2024 (Board names Wynn permanent town
   administrator):
   deltacountyindependent.com/news/paonia-board-of-trustees-selects-stefen-wynn-as-paonias-permanent-town-administrator/article_336ef60a-1607-11ee-bc4c-a3edf9595ac8.html

## Standing QA (enforced every build)
- No client names or engagement details anywhere, in text or baked into images.
- No hourly rates, no personal phone number, no mailing address.
- Every image asset OCR-scanned before packaging.
- Automated dash audit: zero mid-sentence dashes; hyphens only in the compound allowlist.

## Changelog (earlier)
- **v2.4**: Paonia funding record corrected to water only (see above).
- **v2.2** | biography corrected: the 2019 outage was no longer attributed to him;
  moratorium context added; figures added from his own proposal documents.
- **v2.1** | audience voice recentered on residents, customers, and clients served.
- **v2.0** | dash removal with automated audit; What we do de-boxed into four
  general practices; nationwide framing with national awards; governance and
  systems practices added to services.
- **v1.9** | home intro broadened beyond utility rates; adjacent clients introduced.
- **v1.8** | hero cropped above the proposal title block; image OCR QA step added.
- **v1.7** | pages regenerated; full-cover hero introduced; footer contact hard-reset.
- **v1.6** | strategic-wynns.com canonical and og URLs; sitemap.xml; stefen@ email.
- **v1.5** | palette sampled from the real cover artwork; fabricated marks deleted.
- **v1.4 / v1.3** | REVERTED (invented monogram; wrong palette source).
- **v1.2** | no client names without written client approval (standing rule).
- **v1.1** | proposal content: four guiding principles, transparent billing language.
- **v1.0** | initial build.

## Deploy: strategic-wynns.com
1. Netlify Drop (app.netlify.com/drop) or Cloudflare Pages: deploy THIS folder and
   replace any earlier deploy entirely.
2. Point strategic-wynns.com (apex and www) at the host; enable HTTPS. Keep MX
   records with the email provider so stefen@strategic-wynns.com keeps working.
3. After launch: Google Search Console and submit sitemap.xml; Google Business Profile.

## Remaining pre-launch confirmations with Stefen
1. Confirm the ICMA credential is current (annual renewal) before launch.
2. Confirm preferred framing for SRF figures ($9.7M loan with $3M forgiveness, as
   press reported, or the $6.7M net figure from his resume) anywhere else used.
3. Palette vs. printed letterhead (visual check); wordmark typeface or transparent
   logo PNG; About-page headshot; LinkedIn footer link (yes/no).

## Standing content rules
- No client names/logos/engagement details without written client approval.
- No hourly rates published.
- No personal phone number or mailing address published.
- Track record yes; personnel history no.
