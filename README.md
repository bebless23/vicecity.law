# vicecity.law

Static one-page site for **Vice City Attorney**, hosted on GitHub Pages.

## Connect the contact form
1. Create a free form at https://formspree.io and set the email that should receive requests.
2. Copy the form ID (the part after `/f/`).
3. In `index.html`, replace `YOUR_FORM_ID` in the `<form action=...>` with it, commit and push.

## Concept
In-world parody site for a fictional Vice City lawyer. Keep the parody disclaimer in the footer.

## Domain
`CNAME` points Pages at `vicecity.law`. DNS (at your registrar):
- `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `CNAME` for `www`: `bebless23.github.io`
