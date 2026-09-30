# Import–Export Portfolio

Professional portfolio site for **Jagadeeswar Reddy, Supply Chain Analyst** — focused on demand planning, inventory optimization, procurement analytics and import–export operations.

Built with Next.js 16 (App Router), React 19, TypeScript, Tailwind CSS 4, Motion and Lenis. Pages are prerendered as static HTML.

## Run locally

```bash
npm install
npm run dev          # http://localhost:3000
```

Production:

```bash
npm run build
npm start
```

## Pages

| Route | Content |
| --- | --- |
| `/` | Landing — container sky scene; Explore opens the full-screen menu |
| `/about` | Portrait collage, supply-chain narrative, “Why choose me?” |
| `/experience` | Wipro & ICodeTest timeline with KPIs and project cards |
| `/projects` | Case studies with interactive demos |
| `/skills` | Capabilities, tools, certifications |
| `/education` | MSc Purchasing & Supply Chain Management (MBS) |
| `/contact` | Contact details and message form |
| `/resume` | Downloadable CV |

## Content

Typed content lives under `src/content/` (`site.ts`, `about.ts`, `experience.ts`, `projects.ts`, etc.). Replace the PDF in `public/resume/` and update `resume` in `site.ts` to refresh the CV.

## Stack

- Next.js 16 · React 19 · TypeScript
- Tailwind CSS 4 · Motion · Lenis
- Phosphor Icons
