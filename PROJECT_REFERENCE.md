# AI Product Manager Website - Project Reference

**Project Owner**: Jatin Rajvanshi
**Domain**: https://aiproductmanager.ca
**Last Updated**: January 12, 2026
**Purpose**: Personal landing page for free AI Product Management mentorship

---

## 📋 Table of Contents

1. [Project Overview](#project-overview)
2. [Tech Stack](#tech-stack)
3. [File Structure](#file-structure)
4. [Features Implemented](#features-implemented)
5. [SEO & Analytics](#seo--analytics)
6. [Deployment & Services](#deployment--services)
7. [Design & Branding](#design--branding)
8. [Future Enhancements](#future-enhancements)
9. [Quick Commands](#quick-commands)

---

## 🎯 Project Overview

**Goal**: Create a professional landing page to offer free AI Product Management mentorship to people in Canada (especially Vancouver area).

**Target Audience**:
- New graduates seeking first PM role
- Career switchers (developer → PM, business → PM)
- Immigrants navigating Canadian job market
- Professionals wanting to break into AI PM

**Unique Value Proposition**:
- Free mentorship from TELUS AI Product Leader
- 10+ years experience at Fortune 500 (Boeing, NEC, Cognizant) and startups (Meritto, Cymax)
- Bridges tech and non-tech worlds (started hating code, now leads AI products)
- Real production experience with GenAI, LLMs, RAG systems, AI Agents

---

## 🛠 Tech Stack

| Component | Technology |
|-----------|-----------|
| **Frontend** | Pure HTML5 + CSS3 + Vanilla JavaScript |
| **Fonts** | Google Fonts - Syne (headings), Inter (body) |
| **Hosting** | Vercel (auto-deploy from GitHub) |
| **Domain** | Cloudflare DNS → Vercel |
| **Version Control** | GitHub |
| **Analytics** | Vercel Web Analytics |
| **Form** | Google Forms (embedded link) |
| **Logos** | Logo.dev API |
| **SSL** | Vercel (Let's Encrypt) |

**Why This Stack?**
- Zero dependencies, no build process
- Fast loading, no JavaScript frameworks
- Easy to maintain and update
- Free hosting and analytics
- Auto-deploys on git push

---

## 📁 File Structure

```
/
├── index.html                      # Main landing page (29KB)
├── articles.html                   # Articles listing page (NEW)
├── articles/                       # Articles directory (NEW)
│   └── evals-for-ai-agents.html   # First article: AI Agent Evals
├── sitemap.xml                     # SEO sitemap for search engines
├── robots.txt                      # Search engine crawl instructions
├── site.webmanifest               # PWA manifest file
├── google00aff9bda2578ecc.html    # Google Search Console verification
├── README.md                       # Project documentation
├── PROJECT_REFERENCE.md            # This file
└── .git/                          # Git repository
```

**Missing Files (Intentional - Can Add Later)**:
- `favicon.ico` - Browser tab icon
- `favicon-16x16.png` - Small favicon
- `favicon-32x32.png` - Medium favicon
- `apple-touch-icon.png` - iOS home screen icon
- `android-chrome-192x192.png` - Android icon
- `android-chrome-512x512.png` - Large Android icon
- `og-image.jpg` - Social media preview image (1200x630px)

---

## ✨ Features Implemented

### **1. Hero Section**
- Bold headline: "Start Your Journey in AI Product Management"
- Tagline emphasizing tech/non-tech bridge and free mentorship
- Call-to-action: "Let's Connect" (smooth scroll to contact form)

### **2. About Section**
- Current role: Lead PM for AI Agents at TELUS (Chief AI Office)
- Journey: Delhi → 7 Indian cities → Tokyo → Vancouver
- Education: B.Tech (VIT) + MBA (UBC Sauder)
- Self-taught AI expertise

**"What I've Built" Box:**
- 🤖 AI Agents at TELUS (current)
- ✈️ GenAI Chatbot at Boeing
- 🎨 AI Backgrounds for eCommerce (ProductShots.ai)
- 🎓 India's Largest Education CRM (Meritto - 80% universities, 1M+ students)
- 🌏 Mobile App at NEC (LinkedIn Jobs for India-Japan)
- 📊 UBC Product Management Club President

**Tech/Non-Tech Differentiator Box:**
- Highlighted callout explaining journey from hating code to AI Product leader
- Emphasizes ability to guide both technical and non-technical folks

**Company Logos (7 companies):**
- Cognizant, NEC, Meritto, Boeing, Cymax, Creative Destruction Lab, TELUS
- Logos from Logo.dev API with grayscale → color hover effect
- Descriptive SEO-friendly alt texts

### **3. Services Section**
6 service cards:
1. Breaking Into AI PM (tech/non-tech transitions)
2. Resume & Portfolio Review (Canadian market focus)
3. GenAI Product Strategy (RAG, chatbots, LLMs)
4. For New Grads & Students (UBC connections)
5. For Immigrants in Canada (visa, culture, networking)
6. Startup to Big Tech navigation

### **4. Technologies & Domains Section**
Showcases expertise in:
- AI/ML: GenAI, LLMs, RAG Systems, AI Agents
- Industries: Aviation, eCommerce, EdTech, HRTech, Logistics, Finance
- Product Types: Chatbots, CRMs, Marketplaces, SaaS, Mobile Apps
- Tech Background: Java, Python, Microservices, APIs, Blockchain

### **5. Contact Section**
- Headline: "Let's Talk"
- Subtitle: "No sales pitch. No automation. Just real conversations."
- Personal message: "Talking to people gives me joy. That's why I'm doing this."
- Promise box with checkmarks:
  - ✓ Completely free
  - ✓ Personal response from me
  - ✓ We'll schedule a time that works for you
- CTA Button: "Fill Out Quick Form" → Google Form (opens new tab)
- Commitment: "I'll personally email you within 24 hours"

### **6. Must-Read Articles for AI PMs (NEW - January 13, 2026)**

**Homepage Section:**
- Located between Services and Contact sections
- 2-card grid: 1 published article + 1 "Coming Soon" placeholder
- Tagline: "Complex AI concepts explained like we're grabbing coffee"
- CTA: "View All Articles" → `/articles.html`

**Articles Listing Page (`/articles.html`):**
- Navigation: Logo/Home (left) + "Get in Touch" (right)
- Hero section with title and tagline
- 3-column grid (desktop), 1-column (mobile)
- Shows 1 real article + 5 coming soon placeholders
- Each card: Meta info, title, excerpt, tags, link

**Individual Article Structure (`/articles/evals-for-ai-agents.html`):**
- Navigation: "← All Articles" + "Home"
- Header: Title, subtitle, original article reference, reading time
- Content sections:
  1. **Why This Matters to You** - Hook, context, TL;DR callout (300-400 words)
  2. **Key Takeaways** - 6 takeaway cards with PM translations (1000 words)
  3. **What You Can Do** - 3 action boxes by role (400 words)
  4. **First Principles** - 4 concept cards explaining fundamentals (500 words)
- Footer: Original article link + CTAs to contact/articles

**Content Tone:**
- Conversational mentor voice (like talking over coffee)
- Uses "you", "I", "we"
- Short paragraphs, bullet lists, clear headings
- Real-world PM scenarios and analogies
- Honest about complexity and trade-offs

**First Article:**
- Topic: "Understanding AI Agent Evals" (Anthropic's evals guide)
- Original: https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents
- Covers: Grader types, capability vs regression evals, non-determinism metrics, agent-specific strategies
- ~2,500 words, 10 min read

**Design:**
- Matches existing black/white/cyan palette
- Cards: 2px border, 16px radius, hover lift effect
- Section badges: Cyan background (20% opacity)
- Callout boxes: Yellow background, cyan left border
- Max-width: 800px for article content (narrower for readability)
- Larger fonts: 1.15rem body, 1.8 line-height

### **7. Footer**
- Copyright © 2026 Jatin Rajvanshi | Vancouver, Canada
- Email: jatinrajvanshi13@gmail.com
- LinkedIn: https://www.linkedin.com/in/jatin-rajvanshi/
- Attribution: "Logos provided by Logo.dev"

---

## 🔍 SEO & Analytics

### **Meta Tags (Complete)**

**Primary:**
- Title: "Jatin Rajvanshi - AI Product Management Mentor | Vancouver, Canada"
- Description: Comprehensive, keyword-rich (includes TELUS, 10+ years, free mentorship)
- Keywords: AI Product Management, Product Manager Mentor, AI Mentor Vancouver, Product Management Canada, GenAI Product Manager, AI Career Guidance, Tech Mentor Vancouver, UBC Product Management, TELUS AI, Boeing AI, Career Transition AI PM
- Author: Jatin Rajvanshi
- Robots: index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1
- Canonical: https://aiproductmanager.ca

**Open Graph (Facebook/LinkedIn):**
- Type: website
- URL: https://aiproductmanager.ca
- Title, Description, Image (og-image.jpg)
- Locale: en_CA
- Site Name: Jatin Rajvanshi - AI Product Manager

**Twitter Cards:**
- Card: summary_large_image
- Title, Description, Image
- Optimized for Twitter/X sharing

**Geographic Targeting:**
- Region: CA-BC (British Columbia, Canada)
- Place: Vancouver
- GPS: 49.2827, -123.1207 (Vancouver coordinates)

**Additional:**
- Theme Color: #00D9FF (cyan accent)
- Language: en (English)

### **Structured Data (JSON-LD)**

**Person Schema:**
```json
{
  "@type": "Person",
  "name": "Jatin Rajvanshi",
  "jobTitle": "AI Product Manager",
  "worksFor": {"name": "TELUS"},
  "alumniOf": ["UBC", "VIT"],
  "address": "Vancouver, BC, Canada",
  "email": "jatinrajvanshi13@gmail.com",
  "sameAs": ["https://www.linkedin.com/in/jatin-rajvanshi/"],
  "knowsAbout": ["AI Product Management", "Generative AI", "LLMs", "RAG Systems", "AI Agents", "Product Strategy", "Career Mentorship"]
}
```

**ProfessionalService Schema:**
```json
{
  "@type": "ProfessionalService",
  "name": "AI Product Management Mentorship by Jatin Rajvanshi",
  "priceRange": "Free",
  "areaServed": "Canada",
  "serviceType": ["Career Mentorship", "Product Management Consulting", "Resume Review", "AI Product Strategy", "Career Transition Guidance"],
  "geo": {"latitude": "49.2827", "longitude": "-123.1207"}
}
```

### **SEO Files**

**sitemap.xml:**
- Single page sitemap
- Priority: 1.0
- Change frequency: weekly
- Last modified: 2026-01-11

**robots.txt:**
- Allows all user agents (*)
- Sitemap reference: https://aiproductmanager.ca/sitemap.xml
- No disallowed paths

### **Analytics**

**Vercel Web Analytics:**
- Script: `/_vercel/insights/script.js`
- Tracks: Page views, unique visitors, referrers, geography, devices, performance
- Dashboard: https://vercel.com/jatinrajvanshi13s-projects/aiproductmanager-website/analytics

**Google Search Console:**
- Verified via HTML file: google00aff9bda2578ecc.html
- Sitemap submitted: https://aiproductmanager.ca/sitemap.xml
- Will track: Search queries, impressions, clicks, positions, crawl errors

**Current Metrics (as of launch):**
- 10 visitors (first 24 hours, no marketing)
- 80% bounce rate
- No conversions yet

---

## 🚀 Deployment & Services

### **GitHub Repository**
- **URL**: https://github.com/jatinrajvanshi13/aiproductmanager-website
- **Branch**: main
- **Visibility**: Public

**Git Workflow:**
```bash
git add .
git commit -m "Your commit message"
git push origin main
```
→ Vercel auto-deploys in ~30 seconds

### **Vercel**
- **Project**: aiproductmanager-website
- **Dashboard**: https://vercel.com/jatinrajvanshi13s-projects/aiproductmanager-website
- **Default URL**: https://aiproductmanager-website.vercel.app
- **Custom Domain**: aiproductmanager.ca (primary)
- **Auto-Deploy**: Enabled (triggers on push to main)
- **Build Settings**:
  - Framework: Static HTML (no build needed)
  - Output Directory: ./
  - Root Directory: ./

### **Cloudflare**
- **Domain**: aiproductmanager.ca
- **DNS Configuration**:
  - Type: CNAME
  - Name: @ (root)
  - Target: cname.vercel-dns.com
  - Proxy: OFF (gray cloud - DNS only)
  - TTL: Auto
- **SSL Mode**: Full (provided by Vercel)
- **Always Use HTTPS**: Enabled

### **Logo.dev**
- **API Key**: pk_KYsNit5XSBaPdDAjm1qThg (publishable key - safe in client code)
- **Usage**: Company logos for Cognizant, NEC, Meritto, Boeing, Cymax, CDL, TELUS
- **Format**: `https://img.logo.dev/{domain}?token={key}`
- **Attribution**: Required link in footer ✓

### **Google Forms**
- **Form URL**: https://docs.google.com/forms/d/e/1FAIpQLSdoGncsz3TfCQhu1lAJMFQstBNUoK1tFmIEhpItRGEkuwNEFg/viewform?usp=dialog
- **Questions**:
  1. Your Name (required)
  2. Email Address (required)
  3. Current Role/Situation (required)
  4. What brings you here? (multiple choice, required)
  5. Tell me more (paragraph, required)
  6. LinkedIn Profile (optional)
  7. Are you currently in Canada? (optional)
  8. How did you hear about me? (optional)
- **Notification**: Jatin receives email on each submission
- **Follow-up**: Manual email response within 24 hours

---

## 🎨 Design & Branding

### **Color Palette**
- **Primary**: #000000 (Black) - Headings, buttons, footer background
- **Accent**: #00D9FF (Cyan) - Highlights, hover effects, links
- **Text**: #1a1a1a (Near black) - Body text
- **Secondary Text**: #666, #555, #999 - Lighter text
- **Backgrounds**: #ffffff (White), #fafafa (Light gray), #fff9e6 (Warm yellow for callout)
- **Borders**: #e5e5e5, #333

### **Typography**
**Headings (H1, H2, H3):**
- Font: **Syne** (geometric, artistic, distinctive)
- Weights: 400, 600, 700, 800
- Letter spacing: -0.03em to -0.04em (tight, modern)

**Body Text:**
- Font: **Inter** (clean, readable)
- Weights: 200, 300, 400, 500, 600 (mostly 300 for thin, elegant look)
- Letter spacing: 0.01em to 0.03em (airy, spacious)
- Line height: 1.7-1.9 (generous for readability)

**Font Sizes:**
- H1: clamp(2.5rem, 6vw, 5rem) - Responsive, large
- H2: clamp(2rem, 4vw, 3.5rem)
- H3: 1.4-1.8rem
- Body: 1.05-1.2rem
- Small: 0.85-0.95rem

### **Design Philosophy**
- **Clean & Minimal**: Black/white base, single accent color
- **Editorial Feel**: Thin fonts, generous spacing, high-fashion magazine aesthetic
- **Artistic**: Syne font gives unique character
- **Professional**: Strong hierarchy, clear sections
- **Trust-Building**: Company logos, credentials, real story

### **Layout**
- **Max Width**: 1200px (main container)
- **Sections**: Hero, About, Services, Expertise, Contact, Footer
- **Spacing**: 80-120px between sections
- **Responsive Breakpoint**: 768px (mobile)

### **Interactive Elements**
- **Buttons**:
  - Black background, white text
  - Hover: White background, black text
  - Rounded (50px border-radius)
  - Transform on hover: translateY(-2px)
  - Box shadow on hover

- **Cards** (Services):
  - Border: 2px solid #e5e5e5
  - Hover: Cyan border, lift effect, shadow

- **Logos**:
  - Default: Grayscale (100%) + 70% opacity
  - Hover: Full color + 100% opacity

- **Links**:
  - Cyan color (#00D9FF)
  - Underline (2px solid)
  - Opens in new tab (external links)

### **Animations**
- **Hero**: fadeInUp (1s ease-out)
- **Smooth Scroll**: JavaScript for anchor links
- **Transitions**: 0.3s ease on all interactive elements

---

## 🚧 Future Enhancements

### **Recently Implemented (January 13, 2026)**

**✅ Must-Read Articles for AI PMs**
- Homepage section with article cards
- Dedicated articles listing page
- First article: "Understanding AI Agent Evals" (Anthropic)
- Conversational mentor tone for PM audience
- Scalable structure for adding more articles

**Adding More Articles (Process):**
1. Read original technical article
2. Fill content template:
   - Why This Matters: 300-400 words + TL;DR
   - Key Takeaways: 800-1000 words, 4-6 cards
   - What You Can Do: 300-400 words, 3 action boxes
   - First Principles: 400-500 words, 3-4 concepts
3. Copy `/articles/evals-for-ai-agents.html` as template
4. Replace content, update meta tags
5. Add card to `/articles.html` and homepage (optional)
6. Update `/sitemap.xml`
7. Commit and push to deploy

---

### **Discussed but Not Implemented**

**1. Testimonials Section**
- 10-12 testimonials collected (managers, mentees from topmate.io)
- Need to add carousel or grid layout
- Position: After "What I've Built" or before "Let's Talk"
- Format: Photo (optional), Name, Role, Company, Quote

**2. Free Resources Section**
- Ideas discussed:
  - "How to Break Into AI Product Management - 10 Step Guide"
  - "Resume Template for AI PM Roles in Canada"
  - "GenAI Product Manager Interview Prep Checklist"
  - "First 90 Days as an AI Product Manager"
  - Curated Medium articles
- Could add as downloadable PDFs or link to external resources
- Reduces bounce rate by providing immediate value

**3. Bounce Rate Improvements**
Current: 80% (as of launch day)
Strategies to reduce:
- Add statistics banner (10+ years, 7 companies, 1M+ users)
- Make CTA more prominent/larger
- Add secondary CTA (LinkedIn connection - lower commitment)
- Add testimonials for social proof
- Add free resources for immediate value
- Improve above-the-fold content

**4. Missing Assets**
- **Favicons**: Need to create and upload
  - Use https://realfavicongenerator.net/
  - Upload logo (512x512px minimum)
  - Generate all sizes

- **OG Image**: Social media preview (1200x630px)
  - Create in Canva
  - Include: Name + "AI Product Manager" + value prop
  - Upload as og-image.jpg

- **Profile Photo**: For structured data
  - Add profile-image.jpg

**5. Content Additions**
- Blog section (link to Medium or create native)
- Case studies of mentorship success stories
- AI PM resources page
- FAQs section
- Video introduction (YouTube embed)

**6. Features**
- Newsletter signup (Mailchimp/ConvertKit)
- Calendly integration (replace Google Form for direct booking)
- LinkedIn badge/feed integration
- Chatbot for quick questions
- Language toggle (English/French for Canada)

**7. SEO Enhancements**
- Submit to Bing Webmaster Tools
- Build backlinks (guest posts, podcasts, interviews)
- Create blog content for long-tail keywords
- Local business listings (Google My Business)
- Schema markup for FAQs, Articles

**8. Analytics & Optimization**
- Heatmaps (Hotjar/Microsoft Clarity)
- A/B testing (different headlines, CTAs)
- Conversion tracking (form submissions)
- Exit-intent popup (capture leaving visitors)

---

## ⚡ Quick Commands

### **Local Development**
```bash
# Open in browser
open index.html

# Or use a local server
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

### **Git Operations**
```bash
# Check status
git status

# Add all changes
git add .

# Commit with message
git commit -m "Description of changes"

# Push to GitHub (triggers Vercel deploy)
git push origin main

# View commit history
git log --oneline

# Create new branch
git checkout -b feature-name

# Switch branch
git checkout main
```

### **Testing**
```bash
# Validate HTML
# Use: https://validator.w3.org/

# Test structured data
# Use: https://search.google.com/test/rich-results

# Test mobile-friendly
# Use: https://search.google.com/test/mobile-friendly

# Test page speed
# Use: https://pagespeed.web.dev/

# Test Open Graph
# Facebook: https://developers.facebook.com/tools/debug/
# LinkedIn: Just share and preview
# Twitter: https://cards-dev.twitter.com/validator
```

---

## 📞 Important Links

| Resource | URL |
|----------|-----|
| **Live Site** | https://aiproductmanager.ca |
| **Vercel Dashboard** | https://vercel.com/jatinrajvanshi13s-projects/aiproductmanager-website |
| **GitHub Repo** | https://github.com/jatinrajvanshi13/aiproductmanager-website |
| **Analytics** | https://vercel.com/jatinrajvanshi13s-projects/aiproductmanager-website/analytics |
| **Google Search Console** | https://search.google.com/search-console |
| **Google Form** | https://docs.google.com/forms/d/e/1FAIpQLSdoGncsz3TfCQhu1lAJMFQstBNUoK1tFmIEhpItRGEkuwNEFg/viewform |
| **LinkedIn** | https://www.linkedin.com/in/jatin-rajvanshi/ |
| **Logo.dev** | https://logo.dev |
| **Cloudflare DNS** | https://dash.cloudflare.com |

---

## 💡 Pro Tips for Future Sessions

### **When Making Changes**
1. Always read `PROJECT_REFERENCE.md` first
2. Test locally before pushing
3. Commit messages should be descriptive
4. Check Vercel deployment status after push
5. Test on mobile after significant changes

### **Maintaining SEO**
- Update sitemap.xml when adding pages
- Keep meta descriptions under 160 characters
- Test structured data after changes
- Monitor Search Console weekly
- Don't remove Google verification file

### **Performance**
- Keep images optimized (use WebP if adding new images)
- Minimize external scripts
- Use defer/async for non-critical JS
- Monitor Core Web Vitals in Search Console

### **Content Updates**
- Update "Last Modified" in sitemap.xml
- Keep company logos up to date
- Refresh testimonials periodically
- Update metrics (years of experience, etc.)

---

## 📝 Notes & Context

**Project Started**: January 11, 2026
**Launch Date**: January 11, 2026
**Last Major Update**: January 12, 2026

**Original Requirements**:
- Simple but eye-catching page
- Share knowledge about AI Product Management
- Target audience: Canada (Vancouver focus)
- Free mentorship offering
- Email-based connection (no automated scheduling initially)
- Emphasize being a "real human" with verified background

**Key Decisions Made**:
- No JavaScript framework (keep it simple)
- Google Forms over embedded form (easier to manage)
- Logo.dev over Clearbit (better API, free tier)
- Vercel over other hosts (simplicity, auto-deploy, free)
- Syne font for distinctive look
- Black/white/cyan color scheme (minimal, professional)

**What Makes This Project Special**:
- Personal brand for AI Product Management mentorship
- Genuinely free service (no monetization)
- Authentic story (from hating code to AI Product leader)
- Bridges tech and non-tech worlds
- Focus on Canadian market (especially immigrants)
- Self-taught AI expertise (relatable to learners)

---

**End of Reference Document**

*For questions or updates, start a new Claude Code session and reference this file!*
