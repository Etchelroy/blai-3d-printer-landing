SUMMARY: A premium, dark-mode industrial-tech landing page for a 3D printer company that blends precision engineering aesthetics with futuristic visual language — bold typography, glowing accents, and layered depth to evoke innovation and reliability.

---

LAYOUT:

NAVBAR — fixed top, full width, 72px height
- Left: Logo mark + wordmark
- Center: Nav links (Products, Technology, Materials, Company)
- Right: "Get a Quote" CTA button + hamburger for mobile

HERO SECTION — full viewport height (100vh), centered content
- Background: dark layered image with glowing overlay
- Left 55%: Headline text stack + subheadline + two CTA buttons
- Right 45%: Hero product image of printer, floating/elevated treatment
- Bottom: Scrolling ticker bar with stats (Resolution, Speed, Build Volume, Materials)

PRODUCT HIGHLIGHTS — full width, 100px top/bottom padding
- Section label top center
- 3-column card grid, equal width
- Each card: product image top, name, tagline, spec chips, CTA link

FEATURES SECTION — full width alternating layout, 120px padding
- Row 1: Image left (60%), text right (40%)
- Row 2: Text left (40%), image right (60%)
- Row 3: Image left (60%), text right (40%)
- Each row has icon, heading, body text, and inline link

TECHNOLOGY SHOWCASE — full width dark panel, 140px vertical padding
- Large centered section headline
- 4-column icon + stat grid below headline
- Wide cinematic image beneath grid spanning 80% width, centered
- Below image: 2-column split — left body text, right numbered process list

TESTIMONIALS — full width, light-tinted dark panel
- Section label + headline centered
- 3-column testimonial card layout
- Each card: quote text, avatar image, name, company, star rating

CALL TO ACTION — full width, accent gradient band, 120px padding
- Centered: bold headline, subtext, email input + submit button side by side
- Background: geometric mesh pattern with glow

FOOTER — full width, 80px padding
- 4-column: Logo + tagline | Products | Company | Social links
- Bottom bar: copyright, legal links

---

COLORS:

Background Primary: #0A0A0F
Background Secondary: #111118
Background Card: #16161F
Background Light Panel: #1A1A26
Foreground / Surface: #1E1E2E
Accent Primary (Electric Blue): #3B82F6
Accent Glow: #60A5FA
Accent Secondary (Cyan): #06B6D4
Accent Warm (Orange highlight): #F97316
Text Primary: #F1F5F9
Text Secondary: #94A3B8
Text Muted: #475569
Border Subtle: #2A2A3E
Border Accent: #3B82F680
Success Green: #10B981
Gradient 1: linear from #3B82F6 to #06B6D4
Gradient 2: linear from #0A0A0F to #111118

---

COMPONENTS:

NAVBAR:
- Logo: "FORGEVOX" in 700 weight, 22px, Text Primary, with small geometric hex icon in Accent Primary to left
- Nav links: 14px, 500 weight, Text Secondary, spacing 36px between items
- Active/hover state: Text Primary + 2px bottom line in Accent Primary
- CTA Button: "Get a Quote" — 14px, 600 weight, Background Accent Primary, Text white, 10px 20px padding, 6px border radius, hover brightens to Accent Glow with subtle glow shadow

HERO SECTION:
- Eyebrow label: "NEXT-GEN ADDITIVE MANUFACTURING" — 11px, 700 weight, letter-spacing 3px, Accent Cyan, uppercase
- H1 Headline: "Print the" on line 1, "Future." on line 2 — 88px, 800 weight, Text Primary, tight line height 1.0, "Future." in Accent Primary gradient text fill
- Subheadline: 18px, 400 weight, Text Secondary, max-width 480px, line height 1.7
- Primary CTA: "Explore Machines" — large pill button, 16px, 700 weight, Accent gradient fill, white text, 14px 32px padding, 50px border radius, hover lifts with shadow glow
- Secondary CTA: "Watch Demo" — ghost button, same size, white border 1.5px, white text, same radius, hover fills white with dark text
- Ticker bar: 56px height, Background Secondary, marquee animation — 5 stat pairs like "RESOLUTION · 25 MICRONS" separated by dot dividers, 13px, 600 weight, Text Muted / Text Primary alternating

HERO PRODUCT IMAGE:
- Displayed in right panel floated right
- Subtle radial glow behind it: Accent Primary at 20% opacity
- Drop shadow: 0 40px 80px rgba(59,130,246,0.25)
- Floating animation: gentle vertical bob, 4s ease-in-out loop

PRODUCT CARDS (3 total):
- Card size: ~380px wide, rounded 16px, Background Card, Border Subtle 1px
- Product image: 100% width, 220px height, object-fit cover, top rounded
- Card body: 24px padding
- Product name: 20px, 700 weight, Text Primary
- Tagline: 13px, Text Secondary, 8px top margin
- Spec chips: small pill tags, 11px, Background Light Panel, Text Secondary, border Border Subtle, flex row, 12px gap
- CTA link: "View Specs →" — 13px, 600 weight, Accent Primary, bottom of card
- Hover: card lifts 6px, Border Accent glows, product image scales 1.03

FEATURE ROWS:
- Feature image: rounded 20px, full width of its column
- Icon: 48px circle, Background Light Panel, Accent Primary icon inside, 20px border radius
- Feature heading: 36px, 700 weight, Text Primary
- Body: 16px, Text Secondary, line height 1.8, max-width 440px
- Inline link: 14px, Accent Cyan, underline on hover

TECHNOLOGY STATS GRID (4 columns):
- Each cell: centered, icon top (32px, Accent Primary), stat number (56px, 800 weight, gradient text), label below (13px, Text Muted, uppercase, letter-spacing 2px)
- Dividers between columns: 1px vertical, Border Subtle

CINEMATIC IMAGE:
- Width: 80%, height: 500px, border radius 24px, object-fit cover
- Overlay: subtle dark gradient on bottom 30%
- Border: 1px Border Accent

TESTIMONIAL CARDS:
- 360px wide, Background Card, 24px padding, rounded 16px
- Stars: 5 gold stars, 16px, #F59E0B
- Quote: 15px, 400 weight, Text Secondary, italic, line height 1.8
- Avatar: 44px circle image
- Name: 14px, 600 weight, Text Primary
- Company: 12px, Text Muted

CTA BAND:
- Headline: 52px, 800 weight, Text Primary, centered
- Subtext: 17px, Text Secondary, centered, max-width 520px
- Email input: 320px wide, 48px height, Background Card, Border Subtle, 8px radius, left side of pair
- Submit button: "Start Building" — 48px height, Accent gradient, white, 700 weight, 20px 32px padding, attached right side of input pair forming combined unit
- Background: subtle hexagonal mesh SVG pattern, Accent Primary at 4% opacity over Background Primary

FOOTER:
- Logo column: FORGEVOX wordmark, 14px tagline in Text Muted below, social icons row (Twitter/X, LinkedIn, YouTube, Instagram) — 20px icons, Text Muted, hover Accent Primary
- Link columns: 13px, Text Secondary, 10px line gap, column header 11px uppercase letter-spaced Text Muted
- Bottom divider: 1px Border Subtle
- Copyright: 12px, Text Muted

---

INTERACTIONS:

NAVBAR:
- On scroll past 80px: background transitions from transparent to Background Secondary with blur backdrop-filter, 300ms ease
- Nav link hover: color shifts to Text Primary, accent underline slides in from left, 200ms

HERO:
- On page load: H1 animates in with staggered word fade-up, 600ms delay each word
- Subheadline fades in 400ms after headline completes
- CTA buttons slide up together 200ms after subheadline
- Hero image fades in from right with slight translate, 800ms
- Ticker starts scrolling immediately on load, infinite loop
- Background: subtle parallax shift on mouse move — image moves 1.5% opposite to cursor direction

PRODUCT CARDS:
- Hover: translateY(-6px), box-shadow expands to glow blue, border color transitions to Border Accent, 250ms ease
- Image hover: scale(1.03), 300ms ease
- CTA link hover: arrow shifts right 4px, 150ms ease

FEATURE ROWS:
- Scroll-triggered: each row fades and slides in from its direction (image from left, text from right or vice versa) when entering viewport, 600ms ease-out
- Intersection observer threshold: 0.2

TECHNOLOGY STATS:
- Scroll-triggered: numbers count up from 0 to their value over 1200ms when section enters viewport
- Stagger animation on the 4 stat cells, 150ms between each

TESTIMONIALS:
- On mobile: becomes horizontal scroll snap container
- On desktop: cards appear staggered with fade-up, 100ms apart

CTA BAND:
- Email input focus: border glows Accent Primary, subtle inner glow
- Submit button hover: gradient shifts, lifts 2px, glow intensifies
- On submit: button text briefly changes to "Sending…" then "You're in!" with checkmark

GENERAL:
- Smooth scroll behavior site-wide
- All section transitions use scroll-triggered fade-up with 40px vertical offset, 600ms ease-out cubic-bezier
- Cursor: custom cursor dot (8px solid Accent Primary circle) with trailing ring (20px outline) on desktop

---

IMAGES:

HERO BACKGROUND:
https://picsum.photos/seed/industrial-dark-factory/1920/1080

HERO PRODUCT (floating right panel):
https://picsum.photos/seed/3d-printer-machine/900/700

PRODUCT CARD 1 — ForgeVox X1 Pro:
https://picsum.photos/seed/precision-printer-x1/600/440

PRODUCT CARD 2 — ForgeVox S3 Industrial:
https://picsum.photos/seed/industrial-printer-s3/600/440

PRODUCT CARD 3 — ForgeVox MiniLab:
https://picsum.photos/seed/compact-printer-lab/600/440

FEATURE ROW 1 — Precision engineering detail:
https://picsum.photos/seed/engineering-precision-detail/900/600

FEATURE ROW 2 — Materials and filaments:
https://picsum.photos/seed/materials-filament-color/900/600

FEATURE ROW 3 — Software interface / workflow:
https://picsum.photos/seed/software-interface-screen/900/600

TECHNOLOGY CINEMATIC BANNER:
https://picsum.photos/seed/factory-cinematic-wide/1400/500

TESTIMONIAL AVATAR 1:
https://picsum.photos/seed/professional-portrait-one/88/88

TESTIMONIAL AVATAR 2:
https://picsum.photos/seed/professional-portrait-two/88/88

TESTIMONIAL AVATAR 3:
https://picsum.photos/seed/professional-portrait-three/88/88

FOOTER BACKGROUND TEXTURE (subtle):
https://picsum.photos/seed/dark-texture-minimal/1920/400

---

STYLE NOTES:

TYPOGRAPHY:
- Display / Headlines: "Inter" or "DM Sans" — 800 weight for hero, 700 for section heads
- Body: "Inter" — 400 weight, generous line height 1.7–1.8
- Monospace accents (stat numbers, spec labels): "JetBrains Mono" or "IBM Plex Mono" — used sparingly for tech credibility
- Letter spacing on eyebrow labels: 3–4px, all caps, 11px size

SPACING SYSTEM:
- Base unit: 8px
- Section padding: 120px vertical (desktop), 64px (mobile)
- Card gap: 24px
- Grid gutter: 32px
- Max content width: 1280px, centered

FEEL:
- Think Apple meets SpaceX meets high-end industrial catalog
- Dark backgrounds make glowing accents pop dramatically
- Generous white space even on dark backgrounds prevents claustrophobia
- Precision grid alignment throughout reinforces brand of exactness
- Micro-interactions on every interactive element signal quality
- Gradient text used sparingly (headline "Future." and stat numbers only) for visual hierarchy
- Glass-morphism effect on navbar after scroll: backdrop-filter blur(16px) with semi-transparent Background Secondary at 80% opacity
- Subtle grain texture overlay at 3% opacity on hero section for tactile print-like quality
- Section transitions use thin horizontal accent lines (1px, Accent Primary, 60px wide) as section dividers above section labels