# vicecity.law

Static one-page site for **Vice City Attorney**, hosted on GitHub Pages.

## Connect the contact form
1. Create a free form at https://formspree.io and set the email that should receive requests.
2. Copy the form ID (the part after `/f/`).
3. In `index.html`, replace `YOUR_FORM_ID` in the `<form action=...>` with it, commit and push.

## Concept
Two tracks on one page: a fictional Vice City lawyer for game roleplay (the in-game form) and the real attorney section linking to panalawfirm.com. Keep both footer notices; keep jokes out of the real section.

## Domain
`CNAME` points Pages at `vicecity.law`. DNS (at your registrar):
- `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `CNAME` for `www`: `bebless23.github.io`
