# Velocity Motors — Luxury Car Rental Website

## Setup
1. Extract the ZIP.
2. Open the `Velocity-Motors` folder in VS Code.
3. Double-click `index.html` to open it in Chrome, or use the VS Code Live Server extension.
4. Explore the fleet, filter or search cars, click **Rent Now**, choose a pickup and return date, and save a demo booking.
5. Use **My Bookings** to view and cancel reservations.

## Files
- `index.html`: page markup and booking modal
- `style.css`: responsive dark-and-gold styling
- `script.js`: car catalog, filters, booking calculator, and localStorage bookings

## Important limitations
- This is a **frontend-only demo**. Bookings are saved in your browser's `localStorage`, not in a database. Other users cannot see them.
- No real payments, email messages, inventory availability, or authentication are implemented.
- Photos and Google Fonts load from the internet. The page and booking functionality work without internet, but photos and custom fonts will not load offline.
- Prices are illustrative daily rates in Pakistani rupees, not live rental offers.
- The contact form is a demo and does not transmit messages.

## Customize
Edit the `cars` array in `script.js` to update car names, rates, and images. Change colors via CSS variables at the top of `style.css`.

