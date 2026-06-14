# Sadie — artist site

A clean, gallery-style one-page site. A fixed sidebar on the left holds your
name, navigation, and social links; your artwork fills the rest of the screen.
Modeled on the Igor Lipskykh layout: restrained type, the work does the talking.

Everything is in one file: **index.html**. No build tools, no frameworks.

---

## 1. Add your artwork

Make a folder called **paintings** next to index.html and drop in JPGs named:

    paintings/hero.jpg     ← the big image on the opening screen
    paintings/01.jpg
    paintings/02.jpg
    paintings/03.jpg
    paintings/04.jpg

They appear automatically. Until a file exists, a neat placeholder shows the
exact filename to add — so the site never looks broken while you build it.

Tip: wide images suit the hero; the gallery is sized for upright (portrait) work
but any shape is fine.

## 2. Edit the words

Open index.html and search for these markers:

    EDIT ①   your name (top of the sidebar)
    EDIT ②   the navigation links
    EDIT ③   your social links (Instagram, email)
    EDIT ④   painting titles + medium/year
    EDIT ⑤   the About text
    EDIT ⑥   your email + Instagram in Contacts

Each is labeled in a comment right above the thing you change.

## 3. More than four paintings?

Find a whole block that starts with `<figure class="work">` and ends with
`</figure>`, copy it, paste it below the last one, and bump the number.

---

## Putting it online (free)

1. Make a free account at github.com
2. Create a new repository named **yourusername.github.io**
3. Upload **index.html** and your **paintings** folder
4. In the repo: Settings → Pages → set Branch to `main`, Save
5. A minute later your site is live at `https://yourusername.github.io`

To update later: edit index.html on GitHub (the pencil icon), or delete it and
re-upload the new version.
