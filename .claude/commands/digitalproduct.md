---
description: Build a ready-to-sell digital product end to end (concept, content, design brief, pricing, SEO listing, launch posts) for Shopify, Gumroad and Etsy
argument-hint: "[product idea or niche, e.g. 'large-print gratitude journal for seniors', '30 affirmation phone wallpapers']"
---

# /digitalproduct

Take one product idea and turn it into a finished, sellable digital product with a listing ready to publish. Use no paid ads and no inventory, and keep everything doable by a solo creator with AI plus free tools (Canva, Claude).

Product idea from the user (may be empty): $ARGUMENTS

## Brands
- **Floyd Creative Shop**: https://floydcreativeshop.myshopify.com. It sells affirmation cards, digital wallpapers, journals and printables.
- **Floyd Essentials**: affirmations. Instagram @floydessentials.
- **Anchored Movement Co**: large-print fitness and wellness planners. Gumroad store anchoredmovementco.gumroad.com, Instagram @anchoredmovementco.
- **Social**: TikTok @floydcreativeshop, Pinterest Floydcreativeshop, a Facebook page, Mozzieshop.

## Steps

1. **Lock the concept.** If no idea was given, suggest 3 based on the store and social data, or run the `/nichefinder` logic, and ask the user to pick one. Then state the concept in one block:
   - **Product**: name, format (PDF printable, PNG wallpaper pack, Canva template, GoodNotes journal, card deck) and page or item count.
   - **Buyer**: exactly who it's for, and the problem it solves.
   - **Brand**: which brand it belongs to.
   - **Duplicates**: check Shopify and Gumroad for an existing product that overlaps, and say so if there is one.
2. **Write all the content.** Every affirmation, prompt, page heading, instruction and cover line, written in full, not as placeholders. Keep the voice warm, plain and encouraging. If it's large print, keep lines short.
3. **Write the design brief for Canva.**
   - **Size**: page size, or 1080x1920 for wallpapers.
   - **Look**: color palette and font pairing, matched to the brand.
   - **Layout**: per page type.
   - **Mockups**: a list of the images needed (cover, 3 inside pages, a lifestyle shot).

   Then offer to build it with the Canva tools (generate the design, export it as PDF or PNG).
4. **Set the price.** Recommend a price with the reasoning (competitor range, perceived value, where it sits in a bundle). Add:
   - a tripwire version, or a free sample to use as a lead magnet
   - an upsell or bundle
   - one launch discount code idea
5. **Write the listings.**
   - **Shopify and Gumroad**: an SEO title (under 70 characters), a 3-line value proposition, the full description (what's included, who it's for, how to use it, file format and delivery, a no-refunds-on-digital note) and an FAQ.
   - **Etsy**: a title (under 140 characters, keywords first), 13 tags (under 20 characters each), and the description.
6. **Write the launch content for organic traffic.**
   - 5 Pinterest pins: title, description, and a board for each.
   - 3 Instagram/TikTok captions with hashtags: one each for Floyd Essentials, Floyd Creative Shop and Anchored Movement Co where relevant.
   - 1 `/motion` prompt for a 15-second product reel.
   - A 3-email mini launch sequence: an announcement, a peek inside, and a last call on the discount.
7. **Go-live checklist.** List each remaining step and its owner. Then offer to do each one, and wait for an explicit yes before any of them:
   - create a **draft** product in Shopify (digital product) and/or Gumroad
   - upload the file
   - schedule the posts in Metricool
   - add it to the channels dashboard: https://claude.ai/artifact/9EJnkcLTmK3NcFtxpm8K8E

## Rules
- Never publish a product, post on social, send an email or set live prices without the user's explicit approval. Create drafts only.
- Avoid trademarked phrases, characters, and copyrighted quotes. All affirmations and text must be original.
- Don't invent sales numbers. Label every estimate as an estimate.
