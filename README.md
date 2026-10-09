<a href="https://dsvilenkovic.com/"><img src="media/cover.jpg" alt="D. Svilenković Notes, home page on a laptop and a phone" width="100%"></a>

# D. Svilenković Notes

A bilingual notebook where I record why a technical decision was made, what was checked and where the conclusion stops.

**[dsvilenkovic.com](https://dsvilenkovic.com/)** · [Case study (in Serbian)](https://svilenkovic.rs/radovi/d-svilenkovic) · [Srpski](README.sr.md)

> [!NOTE]
> My own project, not client work. The source code is private. This page describes what the site does and how it is built.

<table>
  <tr><td><b>Client</b></td><td>Own project</td></tr>
  <tr><td><b>Industry</b></td><td>Technical notes and decisions</td></tr>
  <tr><td><b>Location</b></td><td>Serbia</td></tr>
  <tr><td><b>Type</b></td><td>Notes website</td></tr>
  <tr><td><b>My role</b></td><td>Research, design, development, SEO and hosting</td></tr>
  <tr><td><b>Stack</b></td><td>Astro 7, TypeScript, PHP 8.3, SQLite, nginx</td></tr>
</table>

## About the project

A finished site does not always show why a decision was made. On dsvilenkovic.com I write down the reasons, the limits and the points that need another check, so the conclusion does not stay only in a conversation or a commit message.

The home page links the notes into a constellation, because architecture, accessibility, reliability and delivery affect each other, and a reader can come in through whichever problem they have. Each note opens with a concrete question, then says what was checked and where the conclusion ends. The motion only shows the connections; the meaning is in the headings and the text, and the pages work without JavaScript.

## What I built

- Notes organised around decisions, with pages for architecture, reliability, accessibility and delivery
- One pattern for each note: the question, what was checked and the limits of the conclusion
- Constellation navigation with ordinary links underneath
- Readable type, visible keyboard focus and reduced motion support
- Serbian and English versions of every note

## Results

| | Performance | Accessibility | Best practices | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Mobile | 98 | 100 | 100 | 100 |
| Desktop | 94 | 100 | 100 | 100 |

PageSpeed Insights, lab test of the live site, October 2026. Security headers: 6 of 6. axe accessibility check: no violations. Structured data: `Organization`, `Person`.

## Screenshots

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="D. Svilenković Notes, home page on a 1440 px screen"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="D. Svilenković Notes, home page on a phone"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Notes index on the live site">
<sub>Notes index on the live site</sub>

---

<sub>Built by [D. Svilenković](https://svilenkovic.com).</sub>
