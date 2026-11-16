# Eligijus Krėpšta

Lead full-stack engineer. I build with TypeScript, React, Node.js and Shopify. Based in Lithuania, available now for remote work.

## Mika Cart Permalinks

My own public Shopify app: [apps.shopify.com/mika-cart-permalinks](https://apps.shopify.com/mika-cart-permalinks)

It turns cart-link setup (variants, subscription plans, discount codes, UTM tags) into a one-click flow for marketers who do not write code. I built and run it alone: spec, build, OAuth, App Store listing, review and merchant support. About 80 installs, all organic. It passed App Store review on the first submission with no requested changes.

## Selected work

Most of my work is in private repositories, so here are three short descriptions instead.

**Shopify purchase-to-access pipeline (Sounds True)**

Turns Shopify orders into app accounts and access to digital products, including entitlements on Thinkific, Mighty Networks and Uscreen, for hundreds of thousands of customer accounts. Every handler is idempotent and failed webhooks retry automatically. A background job replays each customer's order history to correct drift. Repeated failures lock the record and alert the team. Data in and out of every integration is logged, which is how we found customers silently blocked by a third-party platform.

**CMS migration to Sanity behind an unchanged GraphQL API (Sounds True)**

Moved two years of content (around 10 content types, tens of thousands of records) from an in-house CMS to Sanity. Mappers reproduced the old data shape exactly, so the GraphQL schema and every client app stayed as they were. Both data sources ran as parallel deployments behind a feature flag, and a script compared their output until it was identical. The old CMS stayed in sync as a one-switch rollback. I used it once at launch: service was back within minutes and the cause was fixed the same day.

**Claude plugin for product page localization (a retail client)**

The client runs three country stores in three languages. The plugin clones rich product description pages, translates them into the local languages, uploads the images to Shopify and replaces the description. Human approval is the only manual step. Each page went from 1 to 2 days of work to about 2 hours.

## Stack

TypeScript, React, Next.js, Node.js, PostgreSQL, GraphQL, Shopify.

Also used in production: React Native, Vue.js, NestJS, MongoDB, Prisma, Drizzle, Tailwind CSS, Sanity, Stripe, Docker, Vercel.

## Contact

[LinkedIn](https://www.linkedin.com/in/eligijuskrepsta)
