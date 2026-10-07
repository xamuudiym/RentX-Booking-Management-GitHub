# RentX-Booking-Management# RentX — Rental & Booking Management

A Mogadishu-focused rental management platform for houses, apartments, furnished homes, offices and hotel/serviced units.

## Included
- Responsive management dashboard
- Property and unit model
- Customer/tenant and landlord model
- Daily/weekly/monthly/custom rentals
- Booking lifecycle
- Payments, deposits and invoices
- Maintenance
- AI assistant architecture
- Somali/English-ready UI
- USD-first finance
- EVC Plus / Zaad / Sahal / bank / cash payment model

## Run
1. `npm install`
2. Copy `.env.example` to `.env`
3. Set `DATABASE_URL`
4. `npx prisma generate`
5. `npx prisma migrate dev --name init`
6. `npm run dev`

Open http://localhost:3000.
