# Ford Focus ST MK3

Static, responsive single-page site. No build step or package installation is required.

## GitHub Pages

Commit and push these files to `master`. In Settings > Pages, select **Deploy from a branch**, **master**, and **/ (root)**. The root `index.html` is the entry point; `.nojekyll` disables Jekyll processing.

Expected project URL: https://avocadowitharms.github.io/choufmiford/

## Photos

Photo placeholders are intentional and the site can be published before photos are added. Put vehicle photos in `assets/` at the repository root, then set the five paths at the top of `app.js`: `hero`, `front`, `rear`, `interior`, `detail`. Example: `front: 'assets/front.jpg'`.

The WhatsApp number and message are configurable in `app.js`.
