# Ṛta — privacy policy and support

The two pages the app stores require, published with GitHub Pages:

- **Privacy policy** — <https://kaniwesi.github.io/rta-privacy/>
- **Support** — <https://kaniwesi.github.io/rta-privacy/support.html>

Both are plain static HTML in the app's own palette. They set no cookies, run no
scripts and load nothing from anywhere else: the one webfont (Cormorant Garamond,
SIL Open Font License, `fonts/OFL.txt`) is served from this repo rather than from
Google Fonts, so reading the policy sends no request to a third party either.

Pages is served straight from `main` (Settings -> Pages -> Deploy from a branch
-> `main` -> `/ (root)`). There is no build step and no workflow: pushing to
`main` publishes within a minute or two.

The policy's revision history is the page's own changelog. Anything that changes
what the app does with information gets committed here before that version of the
app is released, and the date at the top of the page changes with it.

Ṛta is made by Axl Maas · reframeclips@gmail.com
