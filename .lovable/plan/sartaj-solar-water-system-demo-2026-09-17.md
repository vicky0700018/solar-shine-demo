# Sartaj Solar Water System demo

## Outcome
Replace the starter placeholder with a polished solar water heating website and a matching demo CMS using only React, Vite, Tailwind CSS, React state, and localStorage.

## Public experience
- Build a responsive public home page at `/` with a sticky header, hero banner slider, About, Services, Products/Solutions, Projects, Gallery filtering, Testimonials, Contact form, and footer.
- Use the provided Sartaj Solar Water System details everywhere and a restrained orange, engineering-blue, ink, slate, and white visual system.
- Use bundled/static remote-safe demo imagery for solar water systems and rooftop installations; make all public content read from the shared localStorage store.
- Validate contact submissions, save demo leads locally, and show a clear success state.

## Admin experience
- Add `/admin/login` with the requested demo credentials and localStorage session guard.
- Add responsive admin layout and routes for `/admin`, `/admin/services`, `/admin/products`, `/admin/projects`, `/admin/gallery`, `/admin/testimonials`, `/admin/leads`, and `/admin/settings`.
- Provide dashboard totals, recent activity, quick actions, CRUD-style add/edit/delete/toggle workflows, lead status actions, confirmation dialogs, empty states, and mobile sidebar collapse.
- Keep all modules and settings centralized in a browser-only demo store so admin changes immediately update the public site.

## Technical details
- Preserve TanStack Start routing and use route files for every requested path; do not edit generated route tree files.
- Create focused browser-safe data/store/UI helpers under `src/` and use semantic design tokens in `src/styles.css` rather than raw color utilities.
- Add route-specific metadata for every content route and a single shared shell in `src/routes/__root.tsx`.
- Validate with the live preview, responsive Playwright checks, and the current build diagnostics.
