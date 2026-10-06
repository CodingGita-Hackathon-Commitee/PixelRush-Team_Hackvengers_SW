# Project structure

SurplusLink is organized as a set of static HTML pages. Open the root
`index.html` for the landing page; the folders below contain the prototype's
workflow screens and their page-specific assets.

| Path | Purpose |
| --- | --- |
| `index.html` | Landing page |
| `Home_Page/` | Nearby surplus listings |
| `Surplus_Page/` | Create or manage a surplus listing |
| `Request_Page/` | Request food and review recipient details |
| `Confirmation_Page/` | Confirm a food request |
| `Delivery_Details/` | Pickup and delivery details |
| `Analytics_Page/` | Provider impact and analytics |

Some pages use a folder-local `style.css` and image assets. Preserve relative
paths when moving or renaming pages and assets.

## Running locally

Open `index.html` in a browser for a quick preview. A local static HTTP server
is preferable when checking navigation and relative assets. The project
currently has no package manager, build pipeline, or automated test suite.
