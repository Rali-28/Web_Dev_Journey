# Web Development → Full Stack → Software Engineering Roadmap

This path assumes you are starting near beginner level and can study consistently. Move forward when you can build the listed projects without copying a tutorial step-by-step. A realistic pace is 12–24 months part-time, or 6–12 months full-time.

## Chosen development stack

Use this stack consistently once you reach modern front-end development:

- **Astro** as the primary site and application framework.
- **React + TypeScript** for interactive UI components (Astro islands).
- **Tailwind CSS** for styling after learning core CSS.
- **shadcn/ui** for accessible, customizable React UI building blocks in Astro.
- **Zod** for schema validation, **React Hook Form** for complex forms, **TanStack Query** for server-state/data fetching, and **Lucide** for icons when useful.

These tools accelerate delivery; they do not replace learning semantic HTML, CSS fundamentals, JavaScript, accessibility, APIs, Git, testing, or SQL.

## 0. Set up your foundation (Weeks 1–2)

Learn the tools you will use every day:

- Install and use Zed Code Editor, a modern browser with DevTools, Git, GitHub, Node.js, and a terminal.
- Learn files/folders, the command line, package managers (`npm`), and how the web works: browser, server, HTTP, DNS, URLs, and JSON.
- Learn Git basics: `clone`, `status`, `add`, `commit`, `branch`, `pull`, `push`, and pull requests.

**Outcome:** publish a simple personal site and keep all practice projects in GitHub repositories.

## 1. Front-end web foundations (Months 1–3)

### HTML and accessibility

- Semantic elements, forms, tables, media, metadata, and SEO basics.
- Accessible labels, keyboard navigation, headings, alt text, focus states, and sensible document structure.

### CSS and responsive design

- Selectors, cascade, specificity, box model, typography, colors, positioning, Flexbox, Grid, and media queries.
- Mobile-first responsive layouts; use browser DevTools to inspect and fix layouts.
- Learn plain CSS first, then use Tailwind CSS as your primary styling tool.

### JavaScript fundamentals

- Variables, types, functions, scope, arrays, objects, loops, conditionals, modules, errors, and debugging.
- DOM manipulation, events, forms, local storage, `fetch`, promises, `async`/`await`, and APIs.

**Build:**

- [ ] Responsive portfolio page.
- [ ] Product landing page recreated from a design reference.
- [ ] To-do or habit tracker using local storage.
- [ ] Weather, recipe, or movie finder using a public API.

**Ready to advance when:** you can recreate a responsive design and build an interactive JavaScript app independently.

## 2. Modern front-end development (Months 3–5)

### Astro, TypeScript, and React

- TypeScript types, interfaces, unions, generics, narrowing, and typing API data.
- Astro pages, layouts, routing, content collections, static generation, server rendering, and islands architecture.
- React components, props, state, effects, forms, reusable hooks, and error/loading/empty states. Use React only where interactivity is needed.
- Build interfaces with Tailwind CSS and shadcn/ui; learn how to customize components instead of treating them as a black box.
- State management: begin with component state and Context; use TanStack Query for server state. Use Zod and React Hook Form for robust forms.

### Front-end quality

- Component organization, design systems, accessibility testing, performance basics, environment variables, and deployment.
- Unit/component testing with a common toolchain such as Vitest + React Testing Library.

- [ ] Build and deploy an Astro site with React/TypeScript islands, Tailwind CSS, shadcn/ui components, API data, filters, pagination, responsive layout, and tests.

**Job target unlocked:** Junior Front-End Developer, Web Developer, or internship—if your portfolio and core fundamentals are strong.

## 3. Backend and databases (Months 5–8)

### Server-side development

- Use Node.js with TypeScript. Learn one backend framework deeply: Express, Fastify, or NestJS.
- Build REST APIs: routing, controllers/services, validation, pagination, filtering, error handling, logging, and OpenAPI/Swagger documentation.
- Understand authentication: password hashing, sessions versus JWTs, authorization/roles, cookies, CORS, rate limiting, and common security risks.

### Data

- Learn SQL thoroughly: tables, keys, joins, constraints, indexes, transactions, normalization, and migrations.
- Use PostgreSQL as the primary relational database.
- Use an ORM/query builder such as Prisma, Drizzle, or Knex—but keep writing raw SQL too.
- Learn Redis basics for caching, queues, and rate limiting.

- [ ] Build an API for a real workflow—e.g., a booking, inventory, budget, learning tracker, or task-management service—with PostgreSQL, authentication, role-based permissions, tests, and API documentation.

## 4. Become full stack (Months 8–10)

### Connect the whole product

- Integrate your Astro application and React islands with your own API and database.
- Handle real authentication, protected routes, validation on client and server, file uploads, email notifications, and payment integration in test mode where relevant.
- Deepen Astro's full-stack capabilities: static and server rendering, endpoints/actions, middleware, content collections, caching, and deployment.

### Shipping and operations

- Docker fundamentals: images, containers, volumes, environment variables, and Docker Compose.
- CI/CD with GitHub Actions: lint, type-check, test, and deploy on pull request or merge.
- Deploy a full-stack app, configure a custom domain if possible, and learn basic observability: logs, error tracking, uptime, and database backups.

**Flagship portfolio project:** build and deploy one polished, useful full-stack application.

- [ ] A clear problem statement and a usable responsive UI.
- [ ] Secure authentication and authorization.
- [ ] PostgreSQL schema, migrations, and sound data modeling.
- [ ] A documented API or server endpoints.
- [ ] Validation, error handling, loading states, and accessible interactions.
- [ ] Automated tests and CI.
- [ ] A README explaining architecture, tradeoffs, setup, and live-demo link.

**Job target unlocked:** Junior Full-Stack Developer, Web Application Developer, or Software Engineer I at web-focused teams.

## 5. Get the first web-development role (parallel from Month 4 onward)

- Maintain 3–4 high-quality public projects: 1 front-end, 1 API/database project, 1 flagship full-stack project, and your portfolio.
- Make each README recruiter-friendly: problem, stack, notable features, screenshots, live link, setup, and what you learned.
- Practice explaining decisions: why this data model, why this state approach, what was hard, and what you would improve.
- Practice coding interview essentials: arrays/strings, hash maps, recursion, trees, sorting/searching, Big-O, and debugging. Use JavaScript/TypeScript consistently.
- Apply to internships, apprenticeships, junior web/front-end/full-stack roles, freelance work, open-source beginner issues, and local network referrals.
- Tailor your resume to outcomes and projects, not course completion. Show deployed links and GitHub.

## 6. Transition from web developer to software developer (Months 10–18+)

Web development is already software development; the transition is about broadening depth beyond the browser and CRUD apps.

### Core computer science

- Data structures and algorithms: arrays, linked lists, stacks, queues, hash tables, trees, graphs, heaps, sorting, searching, recursion, dynamic programming, and Big-O analysis.
- Operating systems: processes, threads, memory, files, scheduling, and concurrency fundamentals.
- Networking: TCP/IP, HTTP/HTTPS, DNS, TLS, proxies, load balancers, WebSockets, and failure modes.
- Databases deeper: query plans, indexes, isolation levels, locks, replication, and tradeoffs between relational and document stores.

### Software engineering practices

- Write maintainable code: modular architecture, SOLID as a guideline, dependency boundaries, refactoring, code reviews, and meaningful documentation.
- Test at multiple levels: unit, integration, API/contract, end-to-end, and regression tests.
- Learn observability: structured logging, metrics, tracing, alerting, and incident basics.
- Read existing production code and contribute small, reviewed changes.

### Systems and scale

- Design services around requirements: latency, availability, correctness, cost, security, and maintainability.
- Learn caching, background jobs, message queues, idempotency, retries, rate limiting, file/object storage, and eventual consistency.
- Study system-design basics: load balancing, database scaling, service boundaries, monoliths versus microservices, and API versioning.
- Learn a cloud platform at practical depth (AWS, Azure, or GCP): compute, managed databases, object storage, IAM, networking, and monitoring.

### Broaden your programming model

- Go deeper in TypeScript/Node.js first, then learn one second language based on target roles: Python, Java, C#, Go, or Kotlin.
- Build one non-UI or systems-adjacent project: a CLI, job queue worker, URL shortener with analytics, real-time chat, file-processing pipeline, or small compiler/interpreter.

**Job target:** Software Engineer / Software Developer roles, initially strongest in backend, full-stack, platform-adjacent, or product-engineering teams.

## Suggested learning sequence

| Stage | Primary stack | Evidence of progress |
| --- | --- | --- |
| Web basics | HTML, CSS, JavaScript, Git | Responsive, interactive deployed sites |
| Front end | Astro, React, TypeScript, Tailwind CSS, shadcn/ui, testing | Polished dashboard consuming APIs |
| Backend | Node.js, TypeScript, PostgreSQL | Secure, tested documented API |
| Full stack | Astro, React, API, PostgreSQL, Docker | Deployed flagship product with CI |
| Software engineering | DSA, systems, cloud, second language | Scalable service/CLI and strong technical explanations |

## Weekly rhythm that works

- 60% building: code features, debug, deploy, and improve real projects.
- 20% learning: focused documentation, a course, or reading.
- 10% fundamentals: algorithms, SQL, networking, or system design.
- 10% career work: README, resume, applications, networking, and interview practice.

Keep a short engineering journal: each week record what you shipped, one bug you solved, one concept learned, and the next task. It becomes excellent material for interviews and resume updates.

## Avoid these traps

- Do not endlessly collect courses before building.
- Do not learn five frameworks at once; depth in one practical stack is more valuable early on.
- Do not hide unfinished projects—ship small versions, then iterate.
- Do not skip HTML, CSS, JavaScript, Git, SQL, accessibility, testing, or deployment because a framework feels faster.
- Do not treat certificates as substitutes for a portfolio, work samples, and interview communication.

## First 30 days

- [ ] Set up Git/GitHub, Zed Code Editor, Node.js, and a portfolio repository.
- [ ] Complete HTML/CSS fundamentals and publish one responsive landing page.
- [ ] Complete JavaScript fundamentals and build a local-storage task tracker.
- [ ] Build and deploy a small API-powered app; write a clear README for all three projects.
