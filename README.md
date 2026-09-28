# Suhavi's personal site

A compact, static research page for [suhavi.github.io](https://suhavi.github.io/). GitHub Pages can serve it directly from the root of `main`; there is no build step.

## Editing

`index.html` has comments beside the profile photo, CV, research entries, news, and writing section showing where to add images or links. Put new images and the eventual CV PDF in `assets/`.

- Change the main colors at the top of `styles.css`.
- Replace `assets/profile.jpeg` to change the profile picture.
- Add the revised CV to `assets/`, then uncomment and update the CV link in `index.html`.

To preview locally, run `python3 -m http.server 8000` in this directory and open `http://localhost:8000`.
