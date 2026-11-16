# Bohórquez Lab Secret Santa

Live interface: https://yijialiow.com/gutbrains-secret-santa/

Participants select their name, spin once, and add their wishlist. No account or sign-in is required. Each name's result is saved on the server and can be reopened by selecting that name again. The wheel is centered in the drawing box, with the recipient below it.

GitHub Pages serves `docs/` from `main`, using the personal domain already configured for this account. No additional DNS records are required.

The existing Sites backend stores wishlists and permanent name draws. Only organizer controls (Practice and full-list export) require the organizer's verified account. Selecting Yi Jia in the participant list never grants admin access. The database, organizer email, authentication credentials, and gift assignments are never committed here.

This compiled deployment matches source commit `e6758a512fae85e7b447e3c8b171f58b4b53faa5`, maintained through the existing Sites project.
