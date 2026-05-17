# ImportaAI

**AI-powered platform to source and ship US products to Colombia and South America.**

## Current Status

This repository contains the **MVP web prototype** for ImportaAI.

### Try the Demo

1. Open `index.html` in any modern browser (Chrome, Firefox, Safari).
2. Describe a product (e.g., "iPhone 16 Pro Max", "CeraVe cream", "Nike Air Force 1").
3. Click "Buscar con IA".
4. Explore shipping options, cost breakdown (including Colombian duties & 19% IVA), and complete a simulated order.

The prototype is fully functional offline and demonstrates the core user experience.

## Key Features in Prototype
- Smart product search with realistic examples
- Dynamic shipping options (DHL Express, FedEx, USPS consolidated)
- Accurate landed cost calculator (product + shipping + DIAN tariffs + IVA 19%)
- Currency conversion (USD ↔ COP)
- Clean, modern UI optimized for Colombian users

## Project Vision
Ask buyers what they want → AI finds the best US source, calculates real total cost to Colombia/South America, and handles or guides the purchase & shipping.

## Next Steps (Roadmap)
- [ ] Connect real product APIs (Amazon PA, Walmart, etc.)
- [ ] Live shipping rate integration (DHL, FedEx, Easyship)
- [ ] Real DIAN tariff database / HS code lookup
- [ ] User accounts + order management backend
- [ ] Payment integration (PSE, cards)
- [ ] Mobile app (PWA / React Native)
- [ ] Expansion to Peru, Ecuador, Mexico, Chile

## Tech Stack (Planned)
- Frontend: Next.js / Tailwind
- Backend: FastAPI (Python)
- Database: PostgreSQL / Supabase
- AI: Grok / OpenAI for parsing & recommendations
- Hosting: Vercel + Railway / Fly.io

## Getting Started (Local)
```bash
git clone https://github.com/Chrismiller122580/importaai.git
cd importaai
# Just open index.html in browser
```

## License
Private project — all rights reserved.

Built with ❤️ for Colombians who want easy access to quality US products.

---
**Owner**: Chris Miller (@Cmiller122580) | Started May 2026