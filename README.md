# Sign Up Form

A sign-up landing page built with HTML and CSS for The Odin Project's Intermediate HTML and CSS curriculum.

**[Live Demo](https://anthonyc20b.github.io/odin-signup-form/)**

---

## Screenshot Reference

![Sign Up Form Screenshot](./images/sign-up-form.png)

---

## Screenshot Final Product

![Sign Up Form Screenshot](./images/Screenshot%202026-06-07%20at%204.58.11 PM.png)

---

## Features

- CSS-only form validation using pseudo-classes — no JavaScript
- Error and success states on form fields
- Custom branding and styling
- Flexbox layout

---

## Built With

- HTML5
- CSS3

---

## Design Decisions

The layout, structure, and color palette are a close match. The one intentional difference is label casing — the reference uses all caps, but I went with sentence case since it's more in line with standard readability and accessibility practices.

| Element | Reference | Mine |
|---|---|---|
| Split layout | ✅ | ✅ |
| ODIN branding | ✅ | ✅ |
| Two-column form | ✅ | ✅ |
| Button styling | ✅ | ✅ |
| CSS validation | ✅ | ✅ |
| Label casing | All caps | Sentence case |

---

## What I learned

Flexbox clicked for me on this project. I'd used it before but this was the first time I felt like I was actually controlling the layout rather than guessing until it looked right. Scaffolding out the project, how each section needed to be structured, and how I would setup each container for efficient styling. 

The bigger surprise was how much you can do with CSS pseudo-classes. I went in assuming form validation meant writing JavaScript — turns out `:invalid` and `:focus` cover a lot of ground on their own. That was a useful thing to learn before reaching for a script.

---

## Known limitations

- Designed for desktop — it holds up okay at different widths but it's not truly responsive
- No backend, so the form doesn't actually submit anything
- CSS validation has its limits; a real form would need JavaScript for things like matching password fields

---

## Running locally

Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/anthonyc20b/odin-signup-form.git
```

Or just use the [live demo](https://anthonyc20b.github.io/odin-signup-form/).