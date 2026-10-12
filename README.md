# cv

Personal website of Roger Casals-Franch, served by GitHub Pages at <https://rogercasalsfr.github.io/cv/>.

Plain HTML and CSS, no build step. Push to `main` and the site updates within a minute or two.

| File | What it holds |
|---|---|
| `index.html` | All content. Each section is marked with a `<!-- ==== NAME ==== -->` comment. |
| `style.css` | Layout and colours (light/dark tokens at the top). |
| `assets/Roger_Casals-Franch_CV.pdf` | The CV behind the "Download CV" buttons (referees removed). |
| `favicon.svg` | Browser-tab icon. |

## Common updates

- **New paper:** copy an `<li>` inside `<ol class="pubs">` and edit it. Badges: `badge-ok` (accepted/published), `badge-rev` (under revision), plain `badge` (preprint).
- **New project:** copy an `<article class="card project">` block.
- **New CV:** replace `assets/Roger_Casals-Franch_CV.pdf`, keeping the same file name.

Preview locally with `python3 -m http.server` and open <http://localhost:8000>.
