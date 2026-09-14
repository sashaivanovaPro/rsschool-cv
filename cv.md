# Aleksandra Ivanova

<img src="https://avatars.githubusercontent.com/sashaivanovaPro?v=4" alt="Aleksandra Ivanova Avatar" width="300">

## Contacts

- Location: Bishkek, Kyrgyzstan
- Phone: +996 998 78 58 68
- E-mail: sashaivanova.pro@gmail.com
- GitHub: [sashaivanovaPro](https://github.com/sashaivanovaPro)
- LinkedIn: [sashaivanovaPro](https://www.linkedin.com/in/sashaivanovaPro)
- Telegram: [@sashaivanova_frontend](https://t.me/sashaivanova_frontend) (preferred way of communication)
- Discord: sashaivanova

## About me

Frontend developer. Currently I build an LMS platform for a private school network from scratch — a multi-role system with lesson scheduling, homework workflows and teacher/manager tooling. My focus is scalable architecture and maintainable code: layered component pipeline, reactive state, clear boundaries between modules.

I am growing toward frontend architecture — designing patterns that let a team scale without pain.

Former physician (10 years in anesthesiology, critical care and nephrology). I am drawn to medtech — interfaces where domain complexity is the real challenge.

## Skills

- Languages: TypeScript, JavaScript (ES6+), HTML5, CSS3
- Frontend: React, MobX, SCSS (Sass)
- Architecture: MVVM, Atomic Design, layered pipeline (Store → ViewModel → Adapter → Presenter)
- Tooling: Git, Vite, Webpack, npm, ESLint, Vitest
- Workflow: REST API, Jira, Confluence, Figma, code review, ADR

## Code example

```typescript
type RouteParam = string | number | undefined;

export const curriculumRoute = (
  curriculumId: RouteParam,
  courseId: RouteParam,
): string => `/teaching/curriculum/${curriculumId}?groupCourseId=${courseId}`;

export const planningRoute = (
  curriculumId: RouteParam,
  courseId: RouteParam,
): string =>
  `/teaching/curriculum-schedule/${curriculumId}?groupCourseId=${courseId}`;

export const teachingRoute = (
  curriculumId: RouteParam,
  courseId: RouteParam,
): string =>
  `/teaching/production-unit/${curriculumId}?groupCourseId=${courseId}`;
```

## Work experience

**June 2025 – present** — **Frontend Developer**\
«Дети и наука», Moscow  
LMS platform for a private school network

_Application built from scratch in a small team. Released on September 1, 2026._

- Implemented features across the full layer stack: Store → ViewModel → Adapter → Presenter (MVVM, Atomic Design), reactive state on MobX.
- Authorization and role-based access: multi-role system (teacher, student, parent) with role-dependent data loading.
- Fixed race conditions in view-model rebuilds that lost user input during concurrent updates.
- Gradual migration away from legacy DTOs without stopping feature delivery.
- Data orchestration boundaries for asynchronous loading between independent modules.
- Integration with an evolving backend: working against API contracts that are still changing, and keeping the frontend in sync with the source-of-truth documents.
- Responsive foundation: shared breakpoints and container primitives instead of scattered media queries.

**Stack:** TypeScript, React, MobX, SCSS, Vite, Vitest.

## Education

- **RS School** — JavaScript/Front-end, Stage 1 (2026, in progress)
- **RS School** — JavaScript/Front-end, Stage 0 (2023)
- **ITC Bootcamp Bishkek** — Frontend JS intensive course (2023)
- **Microsoft Learn** — «Build JavaScript applications using TypeScript», «Introduction to version control with Git» (2024)
- **Samara State Medical University** — General Medicine, MD (2005)
  - Postgraduate certificate: Anesthesiology and Critical Care Medicine (2006, about 8 years of practice)
  - Postgraduate certificate: Nephrology, hemodialysis (2021)

## Languages

- **Russian** — native
- **English** — B1 (Intermediate); [EF SET B2 Upper Intermediate](https://efset.org/cert/wavEMQ)
- **French** — B1 (DELF B1, 2014)
