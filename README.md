# FreeStand × Pampers — Onboarding Demo Hub

Interactive demo of Pampers sampling-to-loyalty journeys, in the FreeStand demo UI.

1. **Claim to loyalty**: an ad leads to a web form on pampers.in, with phone OTP on WhatsApp. Date of birth and weight allocate the size, then qualification checks run. After the claim, delivery, day-3 feedback, Pampers Club (buy 4, get the 5th free), receipt stamps, nudges and the birthday hamper all happen on WhatsApp.
2. **Offline + voice AI**: the parent claims at an in-store stand, gets a size-matched sample, and receives a voice AI verification call (Hindi ↔ English). A confirmed sample leads into the loyalty journey; an unconfirmed one flags the promoter and store for audit.

`index.html` is a self-contained Claude Design export, served as-is by GitHub Pages.
Step through with ← / → or the Previous / Next buttons. Serve over http(s); opening
the file directly from disk works but some browsers restrict embedded frames.
