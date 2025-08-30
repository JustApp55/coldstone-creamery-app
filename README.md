# Cold Stone Creamery App 🍦

This is a modern rebuild of the Cold Stone Creamery website, focused on:

- 🛒 Ordering flow with cart, coupons (`LOVEITBOGO`, `BIRTHDAYBOGO`), tax, and checkout  
- 🎂 Seasonal & signature ice cream menu pages  
- ⭐ Club Rewards signup (Supabase backend)  
- ⚡ React + Vite + Tailwind with Zustand store & Supabase client  
- ♿ Optimized for accessibility + Lighthouse 90+ mobile  

## Tech Stack
- React + Vite + Tailwind  
- Zustand (cart state)  
- Supabase (orders + club signups storage)  
- Vercel (deployment)  

## Supabase
Tables:
- `orders` → stores items, subtotal, discount, tax, total, email  
- `club_signups` → stores email signups  

RLS: insert-only for `anon` role.  

## Next Steps
Lovable.dev will scaffold components, wire Supabase, and deploy live preview to Vercel.  
