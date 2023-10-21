# Vercel - Chakra UI - Next JS starter

Template built on [Next.js](https://nextjs.org/), [Suppabase](https://supabase.com/) and [Chakra UI](https://chakra-ui.com/), deployed on [Vercel](https://vercel.com/)

## Deployment Instructions

### Pre requisites

[Suppabase](https://supabase.com/) account and database.

### Steps

- Install dependencies from the root folder - `npm install`

- Rename sample.env to .env and set appropriate variables.

```
  NEXT_PUBLIC_SUPABASE_URL=your-project-url
  NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key
```

You can obtain the connection string by navigating to your Azure Cosmos DB account page's key blade, and select Primary connection string. Copy the value to use.

- Start the project - `npm run dev`

## Demo

TBD

## Vercel + Supabase Integrations

@supabase/auth-helpers-nextjs
@supabase/supabase-js
