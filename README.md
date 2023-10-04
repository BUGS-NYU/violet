# Gallatin (?)

This directory serves as the monorepo for the "Albert Replacement" a.k.a. "Gallatin" project (the name is still under consideration).This won't be a fully fledged Albert replacement, but should serve as a very handy utility that goes hand in hand with Albert system.

## Project Name

Currently, we are calling this project "Gallatin", however we have some doubts about this name as it is also the name of an NYU school, Gallatin School of Individualized Studies. Feel free to suggest a new name for the project. Some possible names:

- **Bobcat** -- NYU mascot
- **Violet** -- official color of NYU
- **Lantern**
- **ArchLink**
- ...

Feel free to add more suggestions by opening a PR.

## Planned Fully-Fledged Project Features

Here are the features that we are plan to implement in the ideal, fully-fledged implementation of the said system:

- Class search and lookup by name, code, professor
  - Possible to filter results by term, year, school
  - See class pre-requisites with links to them
  - Display "Rate My Professor" rating near professor names
- Class link with NYU Syllabi
- Schedule builder with shareable link
  - Commute calculations in the schedule

## Phasing

Project is rather large, so it makes sense to reduce it to some granular implementation phases. Glossary is not well defined for how the features should be called.

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

- Add support for multiple schedules
- Add commute estimations in "My Schedule" page
- Add shareable links to personal schedules

## Implementation

The "Gallatin" system should be the premier interface to interact with "Schedge" API and hence we should mostly focus on leveraging the existing "Schedge" functionality. We may need to implement additional server-side functionality on top of "Schedge", but most of this project is client-side work. Hence, it makes sense to use a framework like **Next.js** that supports both client and server layers.
