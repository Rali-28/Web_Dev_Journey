# HTML Mastery Roadmap

HTML is the structure and meaning of a web page. Learn to make pages understandable to people, browsers, search engines, and assistive technology before adding visual styling or JavaScript behavior.

Use Zed Code Editor, a browser, browser DevTools, Git, and GitHub. Preview every project in a browser and validate it with the [W3C Markup Validation Service](https://validator.w3.org/).

## Stage 1: HTML document basics (Days 1–3)

Learn:

- The document structure: `<!doctype html>`, `<html>`, `<head>`, and `<body>`.
- Elements, tags, attributes, nesting, indentation, comments, and HTML entities.
- Head metadata: character set, viewport, `<title>`, and page description.
- Text: headings, paragraphs, emphasis, strong importance, links, images, line breaks, and horizontal rules.

### Project: Personal profile page

Create a one-page profile with:

- [x] A meaningful title and meta description.
- [x] Your name as the single `<h1>`, followed by logical heading levels.
- [x] A short bio, profile image with useful alt text, and links to relevant sites.
- [x] A favorites list and a small quote or contact section.
- [x] 🍾 Project Complete! 🍾 

**Mastery check:** you can create a valid HTML document from an empty file and explain why heading levels must be ordered logically.

## Stage 2: Semantic page structure (Days 4–7)

Learn:

- Landmark elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`.
- When to use `<div>` and `<span>`—only when no semantic element describes the content.
- Ordered, unordered, and description lists.
- Relative versus absolute links; internal page anchors.

### Project: Multi-page recipe website

Create at least three pages: home, recipe detail, and about/contact.

- [ ] Use a shared navigation menu on every page.
- [ ] Make a recipe article with ingredients as a list, numbered cooking steps, prep/cook times, servings, and a related-recipes aside.
- [ ] Add anchor links that jump from a table of contents to recipe sections.
- [ ] Use meaningful filenames and relative links.
- [ ] 🍾 Project Complete! 🍾 

**Mastery check:** you can choose the appropriate semantic element for each major page region without relying on `<div>` for everything.

## Stage 3: Media, links, and useful content (Week 2)

Learn:

- Images: `alt`, dimensions, captions with `<figure>` and `<figcaption>`, responsive image concepts, and when an image should have empty alt text.
- Audio/video basics, embeds, iframes, and safe/appropriate embed usage.
- Download links, email links, telephone links, and external-link considerations.
- Code-oriented elements: `<code>`, `<pre>`, `<kbd>`, `<samp>`, `<time>`, `<address>`, and `<blockquote>`.

### Project: Travel guide article

Create a long-form destination guide.

- [ ] Include a table of contents with anchor links.
- [ ] Use figures and captions for photographs.
- [ ] Include a map or video embed with a clear title.
- [ ] Add a day-by-day itinerary using `<time>` elements.
- [ ] Add a packing checklist and useful resource links.
- [ ] 🍾 Project Complete! 🍾

**Mastery check:** every image has intentional alt text, and embeds have an accessible title or context.

## Stage 4: Tables and structured information (Week 3)

Learn:

- Tables for data only—not page layout.
- `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>`, `scope`, and basic column/row spans.

### Project: Course or event schedule

Create a schedule page with:

- [ ] A caption explaining the table.
- [ ] Clearly scoped headers for rows and columns.
- [ ] A footer row with totals or notes.
- [ ] A separate detail page for an event or course, linked from the schedule.
- [ ] 🍾 Project Complete! 🍾

**Mastery check:** a screen-reader user can understand what each cell represents from your table headers.

## Stage 5: Forms and accessible input (Weeks 3–4)

Learn:

- `<form>`, `action`, `method`, `name`, and `autocomplete`.
- Inputs: text, email, password, number, date, radio, checkbox, file, range, and hidden fields.
- `<label>`, `<fieldset>`, `<legend>`, `<select>`, `<option>`, `<textarea>`, `<button>`, and `<datalist>`.
- Native validation: `required`, `minlength`, `maxlength`, `min`, `max`, `pattern`, and suitable input types.
- Accessible instructions and error-message structure. Use native HTML first; do not use placeholders as labels.

### Project: Membership or event registration form

Create a form that collects realistic information:

- [ ] Personal information, contact preferences, a date, and optional notes.
- [ ] Group related options using fieldsets and legends.
- [ ] Associate every control with a visible label.
- [ ] Use appropriate autocomplete tokens where relevant.
- [ ] Add helpful instructions, required fields, and native validation.
- [ ] 🍾 Project Complete! 🍾

**Mastery check:** the entire form can be completed using only a keyboard, and every field has a visible label.

## Stage 6: Accessibility, metadata, and professional polish (Week 4)

Learn:

- The language attribute, logical heading order, landmarks, link text, image alternatives, form labels, and keyboard-first review.
- Page titles and descriptions unique to each page.
- Basic Open Graph metadata for sharing.
- `robots` meta tag basics and why semantic content helps SEO.
- HTML validation and how to fix warnings rather than ignoring them.

### Capstone: Accessible small-business website

Build a 4–5 page site for a fictional business, nonprofit, or community group:

- [ ] Home, services/products, about, blog/news article, and contact/booking form.
- [ ] Logical navigation and breadcrumbs or clear page context.
- [ ] At least one well-structured article, table, figure, and form.
- [ ] Unique title and description metadata per page.
- [ ] Fully semantic landmarks and a keyboard-accessibility pass.
- [ ] A `README.md` explaining pages, HTML features used, validation result, and what you would add with CSS/JavaScript.

Publish it using GitHub Pages or another static-hosting service.

## Project progression at a glance

| Project | Main skills | Completion standard |
| --- | --- | --- |
| Personal profile | Document structure, text, links, images | Valid one-page semantic profile |
| Recipe site | Multi-page navigation, landmarks, lists | Three linked pages with semantic recipe article |
| Travel guide | Figures, anchors, embeds, rich text | Accessible long-form article |
| Schedule | Tables and headers | Data table with caption and correct scope |
| Registration form | Labels, fieldsets, validation | Keyboard-friendly, clearly labeled form |
| Business-site capstone | All HTML fundamentals | Deployed, validated multi-page site |

## Daily practice routine

- Spend 30–60 minutes reading and writing HTML deliberately.
- Build each project without copying a complete tutorial.
- Open DevTools and inspect the DOM to see how the browser interpreted your markup.
- Run the validator when you finish a project; fix errors and understand each fix.
- Test keyboard navigation with `Tab`, `Shift + Tab`, `Enter`, and `Space`.
- Commit meaningful progress to Git: `git add .`, `git commit -m "Build accessible registration form"`, then push to GitHub.

## You have mastered HTML when you can

- Start a clean, valid page without a template.
- Structure a multi-page site with semantic landmarks and logical headings.
- Build accessible forms and data tables.
- Write appropriate image alt text and descriptive link text.
- Add correct basic metadata for a page.
- Find and fix HTML issues using browser DevTools and a validator.
- Explain why a chosen HTML element conveys the meaning of its content.

## What comes next

After the capstone, begin CSS. Keep improving the same business-site project while learning layout, typography, responsive design, Flexbox, Grid, and visual accessibility. Avoid jumping into JavaScript until you can confidently create accessible page structure with HTML and style it responsively with CSS.
