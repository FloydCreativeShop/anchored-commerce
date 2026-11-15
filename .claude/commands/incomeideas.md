---
description: Ranked income ideas for Floyd Creative Shop and Anchored Movement Co, built from live store and social data
argument-hint: "[optional focus, e.g. affirmations, planners, Pinterest, $500 this month]"
---

# /incomeideas

Generate income ideas for the user's brands. Base them on the real store and social data, not on general advice.

Focus from the user (may be empty): $ARGUMENTS

## Brands and channels
- **Floyd Creative Shop**: https://floydcreativeshop.myshopify.com. It sells affirmation cards, digital wallpapers, journals, printables, and CJdropshipping products.
- **Floyd Essentials**: affirmations. Instagram @floydessentials.
- **Anchored Movement Co**: large-print fitness and wellness planners. Gumroad store anchoredmovementco.gumroad.com, Instagram @anchoredmovementco.
- **Social**: Instagram floydcreativeshop, TikTok @floydcreativeshop, Pinterest Floydcreativeshop, Facebook page, Mozzieshop.
- **Ground rules**: no paid ads, no inventory, and nothing that needs prior experience.

## Steps

1. **Pull current data.** Use whichever connectors are available. If one isn't connected, note it and keep going.
   - **Shopify**: last 30 and 90 days of orders, gross sales, sessions, conversion rate, top products, and social referrers.
   - **Gumroad**: products (published or not, and price), plus sales totals and views for the last 30 days.
   - **Metricool**: brand settings, plus Pinterest, Facebook, Instagram and TikTok reach and clicks for the last 30 days.
   - **Channels dashboard**: https://claude.ai/artifact/9EJnkcLTmK3NcFtxpm8K8E. Use it if it's useful.
2. **Find the gaps in that data.** Examples:
   - traffic with no sales
   - products that are drafted but unpublished
   - a channel that's growing while the store link gets no clicks
   - products with views but no purchases
   - best-selling themes that could be bundled or upsold

   Cite the actual numbers.
3. **Generate 10 ideas.** Mix quick wins (live today) with bigger plays (live in 30 days). Give each idea:
   - **The idea**: one line.
   - **Why now**: the data point or trend behind it.
   - **Where it sells**: Shopify, Gumroad, Etsy, or Pinterest/Instagram/TikTok driving traffic to one of those.
   - **Price**: the recommended price, with a one-line reason (anchor, bundle, or tripwire).
   - **Effort**: hours to launch with AI plus free tools (Canva, Claude).
   - **Income estimate**: a conservative monthly range. Show the math: traffic × conversion × price. Label it as an estimate.
4. **Rank the ideas** by income ÷ effort. Mark the **top 3 to do this week**.
5. **For the #1 idea, give a launch kit:**
   - an SEO product title and an Etsy/Gumroad description with keywords
   - 13 Etsy tags
   - 3 Pinterest pin titles
   - 1 Instagram/TikTok caption with hashtags
   - one `/motion` prompt for a 15-second reel
6. **Offer to build it.** For example:
   - create a draft product in Shopify or Gumroad
   - schedule posts in Metricool
   - make the design in Canva

   Never publish, post, or change prices without the user's explicit yes.

## Output
- Use a short table for the 10 ideas, then the top 3, then the launch kit.
- Keep it plain and scannable.
- Don't invent sales figures. Every number is either from a connector or labeled as an estimate.
