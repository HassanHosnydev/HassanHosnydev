# Horizon Technology website

An Arabic and English company website built with Next.js.

## My role

I was the sole frontend developer for this website. I built the company-facing pages and the enquiry forms, working with a team that handled separate backend and VoIP services. I also contributed some Express.js backend work across the wider project; the evidence on this page concerns the website repository, not those separate services.

## What I built

The site uses Next.js App Router, React, and TypeScript. English and Arabic have separate locale routes through next-intl, with RTL support for Arabic. Shared design tokens feed CSS variables and Tailwind utilities so the pages use the same typography, colors, and spacing.

I implemented the multi-step enquiry flow and its API integration. The form collects values and an optional file, prevents duplicate submission while sending, shows success or error feedback, and clears the form after a successful request. Next.js route handlers forward submissions to the separate backend.

The repository also includes localized metadata, canonical and language alternate links, a sitemap, robots configuration, and animation components. I have not included performance scores or responsive-completion claims because those were not established in this review.

## Selected implementation history

These references were checked in the private source repository. They support authorship of specific changes; they are not publicly accessible source-code evidence.

| Date | Reference | Contribution recorded in Git |
| --- | --- | --- |
| 21 July 2026 | [353b280](https://github.com/Horizonz-tech/horizon-front/commit/353b280528da24ea07b62e70b28437539f152b67) | Initial Next.js application setup, attributed to HassanHosnydev. |
| 27 July 2026 | [cf8cefa](https://github.com/Horizonz-tech/horizon-front/commit/cf8cefa7a48b392de38de97a5a05882adbae3f45) | Bilingual company website implementation, attributed to HassanHosnydev with Claude recorded as a co-author. |
| 2 August 2026 | [2a9422b](https://github.com/Horizonz-tech/horizon-front/commit/2a9422b02df93d85b7f2bc5698875687beedb81b) | Multi-step form submission, backend integration, and error handling, attributed to HassanHosnydev. The reviewed diff includes the form component, API helpers, route handlers, and translation updates. |

The deployment workflow has a separate contributor in the history. My ownership claim here is frontend implementation, not every infrastructure change in the repository.

## Verification and source access

The repository is private. The links above require permission from its owner and may return 404 to other visitors. No source code, credentials, or internal service addresses are reproduced here. The Git author shown in these references is HassanHosnydev; the account used to access a repository is not necessarily the account attributed as its commit author.
