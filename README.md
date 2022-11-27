<h1 align="center">ts-maps</h1>

## Randomly generate User and Company and then show (plot) them on the google map

---

## Installation

1. Clone the repository and navigate into the project

```sh
git clone git@github.com:royrustdev/ts-maps.git
cd ts-maps
```

2. Install and Run dev server

```sh
pnpm install
pnpm run dev
```

3. Build for production

```sh
pnpm build
```

4. Preview production build

```sh
pnpm preview
```

---

## Tech-Stack

- `pnpm` - node package manager
- `vite` - development server and `esbuild`
- **Typescript**
- Google Map Javascript API

---

## Known Issues

1. (**warning**) This page is in Quirks Mode. Page layout may be impacted. For Standards Mode use “<!DOCTYPE html>”

-> Cannot add `<!DOCTYPE html>` in `index.html` file. If I do so, map doesn't render.

2. (**error**) Cross-Origin Request Blocked: The Same Origin Policy disallows reading the remote resource at https://maps.googleapis.com/maps/api/mapsjs/gen_204?csp_test=true. (Reason: CORS request did not succeed). Status code: (null).

-> **Solution** - Use private window.

---
