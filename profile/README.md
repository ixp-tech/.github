# IXP

### Digital signage infrastructure designed for real buildings.

**IXP** is a digital-signage operations project with an eventual open-source goal. It is being developed for the people responsible for keeping screens, locations, and information organized—not just for making a display look good in a demo.

**[Visit ixp.cool](https://ixp.cool/)** · **[Public website source](https://github.com/jordaninjohnson/ixp.cool)**

## What exists today

The **local development prototype** includes:

| Area | Implemented in the private application repository |
| --- | --- |
| Data foundation | PostgreSQL 17 schema, migrations, fictional sample data, integrity and organization-boundary checks |
| REST API | FastAPI endpoints for organizations, buildings, locations, logical screens, screen-status editing and draft content metadata |
| Admin interface | React/TypeScript inventory creation and browsing, screen-status edits, draft metadata, and building screen-count reports |
| Engineering validation | Automated API, UI, database and browser-to-PostgreSQL tests, with local-only development setup |

The current **v0.3 admin milestone is in progress**. The API package is `0.2.0.dev0`; **no public application release has been published**.

## Where the project is going

A secure, self-hostable platform that eventually helps building operators understand:

- **Where:** which organization, building, location and screen a display belongs to.
- **What:** which content should appear on each screen.
- **When:** schedules and priorities that govern playback.
- **Whether:** whether a device is connected, healthy and recoverable.

Only the inventory and draft metadata portions are available in the local prototype today. Authentication, media playback, scheduling execution, player provisioning, production deployment, backup/recovery and customer pilots remain future work.

## Availability and licensing

**The application repository is currently private.** It has no published open-source license, downloadable release, hosted service, or supported deployment. IXP is **not yet an open-source distribution or a product for purchase**. The public website code is separate from the private application; making the website source public does not license or distribute the application.

The development API does not authenticate callers. Any internal/local testing must use **fictional data on localhost**. Do not deploy it to a public or shared network.

## Follow the work

- **Project site and status:** [ixp.cool](https://ixp.cool/)
- **Browse the public website source:** [jordaninjohnson/ixp.cool](https://github.com/jordaninjohnson/ixp.cool)
- **Explore the IXP organization:** [github.com/ixp-tech](https://github.com/ixp-tech)

We are interested in practical feedback from facilities teams, AV professionals, system administrators, designers and developers. A public contribution process will come after the application is ready for release.

*Last content review: November 2026. Milestones describe engineering progress, not published releases.*
