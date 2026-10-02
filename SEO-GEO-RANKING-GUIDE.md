# SEO + GEO + Local Ranking Pack for a Food Business

This pack is designed for the Aurelia demo site. Replace every `YOUR...` placeholder with real business information before publishing.

## 1. What actually matters most

1. **Real business information everywhere**
   - Keep the same business name, address, phone, opening hours and website URL on your website, Google Business Profile, Apple Maps, Bing Places, Facebook, Instagram and major local directories.
   - Do not publish fake reviews, fake awards, fake addresses, fake ratings or fake opening hours.

2. **Google Business Profile**
   - Claim and verify the business.
   - Choose the most accurate primary category (for example: Restaurant, Pakistani Restaurant, Cafe, Bakery).
   - Add menu, reservation/order links, real opening hours, services, accessibility details, attributes, photos and regular updates.
   - Ask real customers for honest reviews and reply to them.

3. **On-page SEO**
   - Give every important page one clear search intent.
   - Use a descriptive `<title>` and meta description.
   - Use one meaningful H1.
   - Mention cuisine, neighborhood/city, signature dishes and services naturally in visible text.
   - Add descriptive alt text to images.
   - Link internally between Home, Menu, About, Reservations/Order, Contact and Location pages.

4. **Local SEO**
   - Create a strong Contact/Visit page with full NAP (name, address, phone), map, parking/access notes, landmarks and opening hours.
   - If there are multiple branches, create one unique page per branch.
   - Build citations from legitimate local directories, food guides, chambers, delivery platforms and relevant publications.
   - Earn local links through events, suppliers, collaborations, press and community sponsorships.

5. **Content strategy**
   Publish useful content people actually search for:
   - menu and prices
   - dietary options (halal, vegetarian, vegan, gluten-conscious, etc. only if true)
   - catering
   - private dining
   - birthday/event packages
   - delivery areas
   - seasonal menu updates
   - chef stories
   - ingredient sourcing
   - “best dishes for…” style guides based on your actual menu
   - neighborhood guides connected to your location

## 2. GEO / AI-search optimization

Google currently says there are no extra technical requirements, special AI files, or special schema required to appear in AI Overviews or AI Mode. The same SEO fundamentals still apply.

For stronger visibility in search engines and answer engines:

- Write important facts as clear text, not only inside images.
- Keep business facts consistent and current.
- Use specific, verifiable details: cuisine, price level, location, hours, booking method, signature dishes and service options.
- Add first-hand information that competitors cannot copy easily: chef background, sourcing, preparation methods, original photos, menu details, FAQs and policies.
- Use headings that answer real customer questions.
- Cite credible external sources when you publish factual guides.
- Make pages fast, crawlable, mobile-friendly and easy to navigate.
- Keep Restaurant/LocalBusiness structured data aligned with what visitors can actually see.
- Build legitimate mentions and links from trusted local and industry sites.

### About `llms.txt`
An optional `llms.txt` file is included in this pack for experimentation and machine-readable orientation. Google does **not** require it for AI Overviews/AI Mode, and it should not be treated as a ranking shortcut.

## 3. Recommended site structure

- `/` — Home
- `/menu/` — Full menu, prices, dietary notes
- `/about/` — Business/chef story
- `/reservations/` — Booking details
- `/contact/` or `/location/` — Address, phone, map, hours, parking
- `/catering/` — If offered
- `/private-dining/` — If offered
- `/blog/` or `/journal/` — Only if you can publish genuinely useful content

A one-page site can rank, but dedicated pages give search engines more context and let you target more specific searches.

## 4. Keyword framework

Do not stuff these into every sentence. Build pages around the search intent.

### Commercial/local
- [cuisine] restaurant in [city]
- best [cuisine] restaurant in [area]
- restaurant near [landmark]
- dinner restaurant in [area]
- family restaurant in [city]
- romantic dinner in [city]
- restaurant for birthday dinner in [city]
- private dining in [city]
- catering in [city]

### Menu/dish
- best [dish] in [city]
- [dish] near me
- [dish] restaurant [area]
- [dietary requirement] restaurant [city]

### Brand
- [business name]
- [business name] menu
- [business name] reservations
- [business name] reviews
- [business name] location

## 5. Title and meta templates

### Homepage
**Title:** `[Business Name] | [Cuisine] Restaurant in [City]`

**Meta:** `Discover [Business Name], a [cuisine/style] restaurant in [area, city]. Explore our menu, opening hours, reservations and signature dishes.`

### Menu
**Title:** `Menu & Prices | [Business Name] [City]`

**Meta:** `View the latest [Business Name] menu, prices, signature dishes and dietary options. Book a table or plan your visit in [city].`

### Location
**Title:** `Visit [Business Name] | Restaurant in [Area, City]`

**Meta:** `Find [Business Name] in [area, city]. Get directions, opening hours, contact details, parking information and reservation options.`

## 6. Image SEO checklist

- Use original food and interior photography whenever possible.
- Compress large images and serve modern formats such as WebP/AVIF when practical.
- Use descriptive filenames: `charcoal-ribeye-aurelia.webp`.
- Write useful alt text: `Coal-roasted ribeye with black garlic jus`.
- Add width/height attributes where possible to reduce layout shift.
- Lazy-load images below the fold.
- Keep the hero image high quality but optimized for speed.
- Create a real Open Graph/social share image hosted on your own domain.

## 7. Structured data

Use the most specific relevant type, normally `Restaurant`, which is a subtype of `FoodEstablishment` and `LocalBusiness`.

Recommended fields where accurate:
- name
- url
- image
- telephone
- address
- geo
- openingHoursSpecification
- servesCuisine
- priceRange
- acceptsReservations
- hasMenu/menu URL
- sameAs social/profile URLs

Never add ratings/reviews in structured data unless they are genuine and permitted by the relevant guidelines.

A commented Restaurant JSON-LD template has been added to `index.html`. Fill it with real values and then uncomment it.

## 8. Technical SEO launch checklist

- Connect a real HTTPS domain.
- Add the real canonical URL.
- Replace placeholder/fake contact details.
- Publish `robots.txt` at the domain root.
- Publish `sitemap.xml` at the domain root.
- Replace `YOUR-DOMAIN.com` inside both files.
- Verify Google Search Console.
- Submit the sitemap in Search Console.
- Verify Bing Webmaster Tools.
- Test the page with Google Rich Results Test.
- Check indexing with Search Console URL Inspection.
- Test mobile usability and Core Web Vitals.
- Create a favicon and logo.
- Add analytics and conversion tracking if desired.
- Make sure no important page accidentally has `noindex`.

## 9. Performance / Core Web Vitals

For this demo specifically, remote Unsplash images are attractive but are not ideal for maximum control/performance.

For production:
- download/licence your final photos appropriately
- host optimized copies on your own CDN/domain
- use responsive `srcset`
- preload only the hero image if it helps LCP
- defer noncritical JavaScript
- avoid oversized images
- keep fonts and third-party scripts lean

## 10. Authority and backlinks

Good backlinks for a restaurant/food business:
- city publications
- local food bloggers
- reputable restaurant guides
- event partners
- suppliers/farms
- shopping mall or venue directory (if applicable)
- chambers/business associations
- tourism websites
- universities/offices nearby where relevant
- charities/community organizations you actually support

Avoid buying bulk low-quality links. They can waste money and create spam risk.

## 11. Reviews

- Ask customers after a genuine visit/order.
- Do not gate reviews by only asking happy customers.
- Do not buy reviews.
- Reply professionally to positive and negative reviews.
- Look for repeated feedback themes and improve the product/service.

## 12. Monthly ranking routine

Every month:
- check Search Console queries/pages
- review Google Business Profile insights
- fix incorrect hours or menu information
- add fresh real photos
- answer reviews
- improve weak pages with useful content
- add internal links
- find local partnership/link opportunities
- compare ranking pages for your main searches
- refresh seasonal information

## 13. Files included

- `index.html` — updated with safe social/SEO metadata plus a commented Restaurant schema template.
- `robots.txt` — crawl rules template.
- `sitemap.xml` — sitemap template.
- `schema-restaurant-template.json` — copy-ready Restaurant JSON-LD template.
- `llms.txt` — optional AI-readable summary template; not a Google ranking requirement.
- `SEO-GEO-RANKING-GUIDE.md` — this implementation guide.

## 14. Before publishing

Replace all of these:
- `YOUR-DOMAIN.com`
- real business name
- real address
- real phone
- real email
- real city/area
- real coordinates
- real menu URL
- real social profiles
- real cuisine
- real prices/hours
- all fictional reviews/ratings

The current demo contains fictional details. Search optimization should be based on truthful, user-visible information.
