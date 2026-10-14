# muffinemu.github.io

Serves the root of muffinemu.github.io. Every page here sends visitors to the MuffinEMU site at
[muffinemu.github.io/MuffinEMU](https://muffinemu.github.io/MuffinEMU/), and `robots.txt` points
search engines at its sitemap.

- `index.html`: the root goes to the MuffinEMU home page.
- `404.html`: `/muffinemu/…` and `/Muffin-EMU/…`, in any capitalisation, go to the same page under
  `/MuffinEMU/`; any other missing page goes to the home page.
- `robots.txt`: allows everything and names the sitemap.

The site itself is built from `docs/` in [MuffinEMU/Muffin-EMU](https://github.com/MuffinEMU/Muffin-EMU).
