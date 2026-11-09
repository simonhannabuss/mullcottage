# Mull Cottage

Source for [mullcottage.co.uk](https://www.mullcottage.co.uk/), the website for Achadh-a'Mhullaich, a self-catering holiday cottage on the Isle of Mull, Scotland.

## Contents

| Path | What it is |
|---|---|
| `index.html` | The current live homepage (snapshot of 30 January 2025). The contact section uses an Elfsight form embed. |
| `_assets/index.html` | Earlier version of the homepage (September 2022), with the original PHP contact form (`contact-form.php`). Kept for reference. |
| `_assets/astonish.css` | Main theme stylesheet (the "Astonish" Bootstrap theme). |

## Notes

- The page is a single static HTML file built on the Astonish Bootstrap 3 theme with jQuery plugins.
- Stylesheets, scripts and images load from absolute `https://mullcottage.co.uk/...` URLs, so they are not stored in this repository. Opening `index.html` locally still renders the site while the live server is up.
- Bookings go through Bookster: <https://secure.booksterhq.com/book/38432>.
- Figma rebuild of the current design: <https://www.figma.com/design/cuoVMiyoTxfh28JIVlVzN7/Mull-Cottage>
