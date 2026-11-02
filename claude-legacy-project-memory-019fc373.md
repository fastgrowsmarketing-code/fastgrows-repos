**Purpose & context**

FastGrows operates Fastgrows.com, an AI-powered digital marketing agency and educational platform based in Vadodara, Gujarat, India. The mission is to help businesses, creators, and startups grow through AI, digital marketing, automation, SEO, and social media.

**Services offered:** Social Media Marketing, AI Marketing, SEO, Google Ads, Meta Ads, LinkedIn Marketing, Content Marketing, Blogging, Lead Generation, Marketing Automation, Email Marketing, Website Marketing, Analytics, Marketing Strategy, and Personal Branding.

**Target audience:** Small businesses, startups, entrepreneurs, local businesses, coaches, consultants, B2B companies, and professionals in India.

**Brand identity:** Professional, Friendly, Helpful, Innovative, Trustworthy, Practical, Educational, Honest. Style is modern, minimal, professional, and AI-inspired with clean layouts.

**Ethics:** Never copy content, fact-check all claims, ethical marketing only, focus on long-term growth — not shortcuts.

---

**Current state**

FastGrows is actively producing branded blog content for the Fastgrows blog (fastgrows-ai.blogspot.com), along with associated visual and publishing assets. Recent posts have covered topics including types of advertising and autopilot SMM (Social Media Marketing) posting. Each content production session typically yields:
- A styled HTML blog post following the Fastgrows design system
- A 1200×630 PNG cover image rendered via `wkhtmltoimage`
- Full Blogger publishing metadata (meta title, meta description, URL slug, focus keyword, image alt text, labels)

---

**Key learnings & principles**

- **Cover image rendering:** Google Fonts (Archivo Black, Inter, JetBrains Mono) are unavailable in the render environment due to no network access; system fonts (Liberation Sans, DejaVu Sans, Liberation Mono) serve as stand-ins. Exact-font rendering requires uploaded font files or an external tool (e.g., Canva).
- **Layout iteration is common:** Cover image renders may require adjustments (e.g., font size reduction, repositioning elements) to prevent overlapping text before finalising.
- **Typo tolerance:** Interpret likely input typos charitably (e.g., "SSM" → "SMM") and proceed accordingly.
- **Blog content is India-specific:** Posts use Indian English, India-relevant examples, and target the Indian market.

---

**Tools & resources**

- **Blog platform:** Blogger (fastgrows-ai.blogspot.com)
- **Cover image rendering:** `wkhtmltoimage` (bash tool), output at 1200×630px PNG
- **File handling:** `create_file` tool for HTML post and cover templates; outputs saved to `/mnt/user-data/outputs/`

---

**Approach & patterns**

**Blog design system (fastgrows-ai.blogspot.com):**
- **Fonts:** Archivo Black (headlines), Inter (body text), JetBrains Mono (tags/meta/labels)
- **Brand colors for blog posts:** Orange, Black, White, Yellow
- **Visual elements:** Orange accent bars, yellow tags in JetBrains Mono, h2/h3 heading hierarchy (no h1 tags in post body per blog rules)
- **SEO requirements:** Mandatory internal link (to Fastgrows blog) and external link per post
- **Language:** Indian English throughout

**Brand colors (general):** Orange, Black, White
*(Blog posts additionally use Yellow as part of the updated blog design system)*

#### Memory edits
- Fastgrows.com is user's AI-powered digital marketing agency & educational platform, based in Vadodara, Gujarat, India. Mission: help businesses/creators/startups grow via AI, digital marketing, automation, SEO, social media. Brand: Professional, Friendly, Helpful, Innovative, Trustworthy, Practical, Educational, Honest. Services: Social Media Marketing, AI Marketing, SEO, Google Ads, Meta Ads, LinkedIn Marketing, Content Marketing, Blogging, Lead Gen, Marketing Automation, Email Marketing, Website Marketing, Analytics, Marketing Strategy, Personal Branding. Audience: small businesses, startups, entrepreneurs, local businesses, coaches, consultants, B2B, professionals in India. Brand colors: Orange, Black, White. Style: Modern, Minimal, Professional, AI-inspired, clean layouts. Language register: Indian English, target market India. Ethics: never copy content, fact-check claims, ethical marketing only, focus on long-term growth not shortcuts.
- Fastgrows blog is at fastgrows-ai.blogspot.com. Blog design system: fonts are Archivo Black (headlines), Inter (body text), JetBrains Mono (tags/meta/labels). Updated brand color theme for blog posts: Orange, Black, White, Yellow (supersedes earlier no-yellow rule for blog content).