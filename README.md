# Violet 🟣

This directory serves as the monorepo for the **Violet** project. This won't be a fully fledged Albert replacement, but should serve as a very handy utility that goes hand in hand with Albert system.

## Project Name

**EDIT:** For now, we are settling with the **Violet** name.

Currently, we are calling this project "Gallatin", however we have some doubts about this name as it is also the name of an NYU school, Gallatin School of Individualized Studies. Feel free to suggest a new name for the project. Some possible names:

- **Bobcat** -- NYU mascot
- **Violet** -- official color of NYU
- **Lantern**
- **ArchLink**
- ...

Feel free to add more suggestions by opening a PR.

## Planned Fully-Fledged Project Features

Here are the features that we plan to implement in the ideal, fully-fledged implementation of the said system:

- Class search and lookup by name, code, professor
  - Possible to filter results by term, year, school
  - See class pre-requisites with links to them
  - Display "Rate My Professor" rating near professor names
- Class link with NYU Syllabi
- Schedule builder with shareable link
  - Commute calculations in the schedule

## Phasing

Violet project is rather large, so it makes sense to reduce it to some granular implementation phases. Glossary is not well defined for how the features should be called.

### Phase 1 features

- Look up classes by name, code, potentially professor via home search
- Display search results in a paginated list
- Add support for search result filtering by selecting choosing term, school
- Support click on the classes and display specific class page with relevant class information (e.g. pre-requisites, professor, location etc.)

### Phase 2 features

- Add class linking with NYU Syllabi
- Add "Rate My Professor" integration
- Add "My Schedule" cart and possibility to select and add classes to the user's schedule

### Phase 3 features

- Add CS Wiki Recommended Class More Info if the class is listed there
- Add support for multiple schedules
- Add commute estimations in "My Schedule" page
- Add shareable links to personal schedules

## Implementation

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.
