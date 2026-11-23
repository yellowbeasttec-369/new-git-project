# Munchies Moverz™ — prototype

A mobile-friendly local marketplace concept for growers, tuck shops, merchants, buyers and potential carriers in South Africa.

## Demo features
- Browse and filter sample listings by product, category and town.
- Add listings in the browser.
- Create an order request with quantity, fulfilment date/method and payment terms.
- Generate a draft agreement with typed-name acknowledgements.
- Share listing text through the device share sheet or clipboard.

## Limitations
This is a front-end prototype. Sample listings are fictional examples. User listings and draft orders are stored only in the current browser using localStorage; they are not shared with other people or backed by a server. There is no real authentication, Google OAuth, WhatsApp OTP, Facebook connection, payment handling, carrier verification, notifications, fraud detection or cryptographic/legal e-signature process. Typed names are not proof of identity. Do not use this prototype to handle real payments or sensitive personal information.

## Identity and inclusion principles
- Do not infer identity, nationality, immigration status or honesty from someone's name, accent, ethnicity, Facebook profile or SIM registration.
- Record a person's recognised name and trading name separately; do not force an anglicised name.
- Use proportionate verification and collect only data necessary for the transaction and applicable legal obligations.
- For regulated financial services or higher-risk transactions, obtain legal advice and use a suitably authorised identity/payment provider rather than storing identity documents in this prototype.

## Next steps
1. Connect a persistent database and implement access control.
2. Add Google OAuth and a real phone verification flow; treat them as distinct signals.
3. Add seller/buyer/carrier profiles, agreement snapshots, timestamps and immutable audit events.
4. Add reporting, cancellations, dispute handling and fulfilment tracking.
5. Review POPIA, consumer/e-commerce, electronic-signature, payment and any applicable KYC obligations before live transactions.
