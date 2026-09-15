# Aleksandra Ivanova

<img src="https://avatars.githubusercontent.com/sashaivanovaPro?v=4" alt="Aleksandra Ivanova Avatar" width="300">

## Contacts

- Location: Bishkek, Kyrgyzstan
- Phone: +996 998 78 58 68
- E-mail: sashaivanova.pro@gmail.com
- GitHub: [sashaivanovaPro](https://github.com/sashaivanovaPro)
- LinkedIn: [sashaivanovaPro](https://www.linkedin.com/in/sashaivanovaPro)
- Telegram: [@sashaivanovaPro](https://t.me/sashaivanovaPro) (preferred way of communication)
- Discord: [sashaivanova](https://discord.com/users/1041586408499970071)

## About me

Frontend developer. I am currently building an LMS platform for a private school network from scratch — a multi-role system with lesson scheduling, homework workflows and tools for teachers and managers. I care about scalable architecture and maintainable code: a layered component pipeline, reactive state and clear boundaries between modules.

My goal is to grow into frontend architecture — designing patterns that help a team grow without slowing down.

Before IT, I worked as a physician for 10 years (anesthesiology, critical care and nephrology). I am interested in medtech — products where the domain itself is the hard part.

## Skills

- Languages: TypeScript, JavaScript (ES6+), HTML5, CSS3
- Frontend: React, MobX, SCSS (Sass)
- Architecture: MVVM, Atomic Design, layered pipeline (Store → ViewModel → Adapter → Presenter)
- Tooling: Git, Vite, Webpack, npm, ESLint, Vitest
- Workflow: REST API, Agile/Scrum (sprints, burndown), Jira, Kaiten, Confluence, Figma, code review, ADR, Conventional Commits

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

- **Architecture:** Implemented features across the whole layer stack (Store → ViewModel → Adapter → Presenter; MVVM, Atomic Design) with reactive state on MobX.
- **Access control:** Built a multi-role system (teacher, student, parent) where data loading depends on the role.
- **Stability:** Fixed race conditions in view-model rebuilds that were losing user input during concurrent updates.
- **Migration:** Gradually migrated the app away from legacy DTOs without pausing feature delivery.
- **Data loading:** Defined how independent modules load data asynchronously, so they do not depend on each other.
- **Backend integration:** Worked with a backend that was still changing — followed the API contracts and kept the frontend in sync with the source-of-truth documents.
- **Responsive layout:** Set up shared breakpoints and container primitives instead of scattered media queries.
- **Testing:** Wrote unit and UI tests with Vitest (node and jsdom environments).
- **Refactoring:** Delivered long refactorings as chains of atomic commits (preparation → contracts → logic → UI → integration).
- **Process:** Wrote and maintained ADRs and source-of-truth docs; agreed on API contracts with backend and PM before implementation; every change went through code review.

**Stack:** TypeScript, React, MobX, SCSS, Vite, Vitest.

## Education

- **RS School** — JavaScript/Front-end, Stage 1 (2026, in progress)
- **RS School** — JavaScript/Front-end, Stage 0 (2023)
- **ITC Bootcamp Bishkek** — Frontend JS intensive course (2023)
- **Microsoft Learn** — «Build JavaScript applications using TypeScript», «Introduction to version control with Git» (2024)
- **Samara State Medical University** — General Medicine, MD (2005)
  - Postgraduate certificate: Anesthesiology and Critical Care Medicine (about 8 years of practice)
  - Postgraduate certificate: Nephrology, hemodialysis (2021–2022)

## Languages

- **Russian** — native
- **English** — B1 (Intermediate); [EF SET B2 Upper Intermediate](https://efset.org/cert/wavEMQ)
- **French** — B1 (DELF B1, 2014)
