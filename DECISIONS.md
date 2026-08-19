# ORBIT — DECISIONS

## 1. Product and direction

ORBIT is an invented premium fashion-discovery product: a futuristic Y2K storefront for discovering sneaker edits, streetwear references, and a women's luxury-bag edit. I chose a strong neon/cosmic visual system because the product is about fashion discovery and limited-drop energy, while keeping the interface readable rather than turning every element into an animation.

The hero communicates the value proposition immediately: **“Your closet, in another universe.”** The primary CTA is **“Explore the collection”**, taking the user directly into the product catalogue.

## 2. Product demonstration

The homepage does not rely only on marketing copy. The main shop section contains interactive product cards, search, category filters, hover states, and a luxury-bag section. The drop-radar section provides a second interactive representation of the concept.

The catalogue is explicitly labelled as a **demo/concept catalogue**. Brand names are used as style references only; the page does not claim affiliation, real inventory, customer counts, testimonials, or real product pricing.

## 3. Responsive and interaction decisions

The page is built with plain HTML, CSS and JavaScript so it can ship quickly without a framework. Responsive grids collapse at smaller breakpoints, navigation simplifies on mobile, long content is allowed to wrap, and decorative elements are constrained to the viewport.

The intended validation targets are **390px mobile** and **1440px desktop**, with `max-width: 100%`, responsive grids, mobile-specific spacing, and no intentional horizontal scrolling.

Motion is restrained to useful feedback: the ORBIT visual/radar movement, scroll reveals, and product hover states. Product cards also provide a small local interaction when the user selects an edit.

## 4. One time-limit trade-off

I prioritised a polished, responsive single-page experience over building a real commerce backend, authentication system, payments, or live product APIs. With a real week, I would connect verified product feeds, add real inventory/availability data, implement authentication and saved collections, and add proper accessibility and performance testing across real devices.

## 5. AI usage and verification

AI was used to help iterate on the HTML/CSS/JavaScript structure, visual system, responsive behaviour, product-card interactions, and copy.

I personally reviewed the resulting page structure and kept the implementation as plain HTML/CSS/JS so I can explain the code in a follow-up discussion. I also removed potentially misleading fabricated metrics/prices and added explicit concept/affiliation language so the page follows the assessment's honesty constraint.
