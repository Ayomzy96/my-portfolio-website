# Shininglight Fellowship — Website

This is the online home for Shininglight Fellowship. The site is a clean, responsive front-end built from the "SimpleFolio" template and customized to share fellowship events, resources, volunteer opportunities, and contact information.

Our mission: to worship, serve, and share Christ's light by building a warm, welcoming community where people grow in faith and serve others. (Edit this mission in `README.md` if you'd like a different wording.)

This repository contains a static front-end site (HTML, JavaScript and SCSS) used to showcase profile information, projects, and resources tailored for the fellowship.

## Summary

- Purpose: A lightweight, fast portfolio-style site used by a fellowship to present information, upcoming events, volunteer opportunities and contact details.
- Built with: HTML, vanilla JavaScript, SCSS (Sass) and a small set of front-end libraries (Bootstrap, jQuery, Vanilla-Tilt). Parcel is used as the local dev/build tool.

## Tech stack

- HTML (src/index.html)
- JavaScript (src/index.js, small site scripts in src/scripts/)
- SCSS organized under `src/sass/` (abstracts, base, components, layout, sections)
- Parcel (dev dependency) for local development and builds
- Libraries: Bootstrap, jQuery, Popper, Vanilla-Tilt

## Notable files and structure

- `src/index.html` — main entry page
- `src/index.js` — site script entry
- `src/styles.scss` — compiled stylesheet entry (Sass entry)
- `src/assets/` — images, resume and other static assets
- `src/sass/` — SCSS partials and organization (see folders for sections, components, etc.)
- `src/scripts/` — small helper scripts (scroll reveal, tilt animation)
- `package.json` — dev scripts and dependencies

## Running locally

This project is a static front-end site. There are two simple options to run it locally:

1) Open locally

	 - Open `src/index.html` in a browser. (For many dev workflows a simple static server is preferred.)

2) Using Parcel (recommended for development)

	 - Install dependencies:

		 npm install

	 - Start a development server:

		 npm start

	 - Build for production:

		 npm run build

Parcel will serve the `src` entry (`src/index.html`) and handle SCSS transforms (see devDependencies in `package.json`).

## Customize

- Edit site content in `src/index.html` and `src/index.js` (sections are organized by `src/sass/sections/*` for styles).
- Replace images and documents in `src/assets/`.
- Update styles in the SCSS partials under `src/sass/`.

## Credits

This project is based on the SimpleFolio template. See `package.json` for references to the upstream repository and author.

## License

The project uses the repository license (see `LICENSE.md`).

---

