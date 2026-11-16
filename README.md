# Bohórquez Lab Secret Santa

Live interface: https://yijialiow.com/gutbrains-secret-santa/

Participants select their name, enter the private code sent by the organizer, spin once, and add their wishlist. No ChatGPT account is required. A matching code is required by the backend to draw, reopen a saved recipient, or edit a wishlist. Everyone can read the shared gift list. Locking or selecting another name clears the current tab's access.

GitHub Pages serves `docs/` from `main`, using the personal domain already configured for this account. No additional DNS records are required.

The existing Sites backend stores wishlists, permanent name draws, and private participant codes. Only organizer controls (Practice, full-list export, and participant-code download) require the organizer's verified account. The code download creates missing codes and keeps existing codes unchanged; distribute each person's code individually. Selecting Yi Jia in the participant list never grants admin access. The database, organizer email, authentication credentials, private codes, and gift assignments are never committed here.

This compiled deployment matches source commit `4ddd51884c2f465b7c7083146e12917a6010002e`, maintained through the existing Sites project.
