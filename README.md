# Amir Travelers website (updated)

## Files
- `index.html` — page structure and content
- `style.css` — responsive navy/gold styling, popup booking form, light/dark theme
- `script.js` — Hindi/English toggle, vehicle-count form, per-car vehicle selection, fare estimator and WhatsApp booking message

## Booking calculation
Each selected car is calculated independently using the entered distance:
- Maruti Suzuki Eeco: ₹8/km + ₹800 driver charge
- XL6, Vitara Brezza, Brezza, Ertiga and Toyota Rumion: ₹10/km + ₹1,000 driver charge
- Total estimate = sum of all selected cars' (distance × rate + driver charge)
- Passenger count is optional and does not affect price.
- Toll and parking are extra. Rates may change.

## WhatsApp
The form opens WhatsApp at +91 74519 52707 with a prefilled bilingual booking message. The customer must press Send.

## Publish on GitHub Pages
1. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the root of your repository.
2. Go to **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
4. Open the GitHub Pages URL after deployment.

## Important before publishing
- The online visitor number is explicitly labelled as a demo counter and changes every 20 seconds. It is not a real analytics count.
- Vehicle photos use external manufacturer image URLs where possible. External image URLs can change; test them after publishing and replace with properly licensed exact model photos if needed.
- Confirm vehicle availability, seating variant, rates, driver charges and service terms before accepting bookings.
- `@amirtraveller` is not a complete email address. Replace the temporary mailto link with the correct full email when available.
