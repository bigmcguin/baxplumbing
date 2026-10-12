# Bax Plumbing website

Plain HTML, CSS and JavaScript site for Bax Plumbing, Mount Isa. Hostinger
publishes the repository root to `public_html` whenever `main` changes.

- Pages: `index.html`, `services.html`, `about.html`, `contact.html`
- Colours, fonts and spacing: `assets/css/theme.css`
- Menu items and logo: `NAV_CONFIG` at the top of `assets/components/nav/nav.js`
- Font: Archivo (SIL Open Font Licence), self-hosted in `assets/fonts/`
- Photos: `assets/images/`, WebP at 760 px and full width, used with `srcset`

## Publishing changes to CSS or JS

Pages link to the stylesheets and `nav.js` with a version, such as
`main.css?v=20261012b`. Browsers keep their saved copy until that version
changes, so after editing any CSS or JS file, change the `?v=` value on
every page (all pages use the same value).
