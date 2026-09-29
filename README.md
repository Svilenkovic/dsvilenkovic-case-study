# D. Svilenković Notes

A bilingual notebook for web decisions, tradeoffs and implementation notes that are useful beyond one project.

**[dsvilenkovic.com](https://dsvilenkovic.com/)** · [Srpski](README.sr.md)

> [!NOTE]
> This is an independent project by D. Svilenković. The production source stays in a private repository; this public repository documents the work.

<table>
  <tr><td><b>Type</b></td><td>Technical notes and decisions</td></tr>
  <tr><td><b>Languages</b></td><td>Serbian and English</td></tr>
  <tr><td><b>Public routes</b></td><td>18 canonical pages</td></tr>
  <tr><td><b>Role</b></td><td>Research, design, development, SEO, hosting and maintenance</td></tr>
  <tr><td><b>Stack</b></td><td>Astro, TypeScript, CSS, PHP 8.3, SQLite, nginx</td></tr>
</table>

## Purpose

Project knowledge is easy to lose when it stays inside tickets or source files. This site turns selected decisions into short public notes that explain the context, the tradeoff and the chosen path.

## Design direction

The reading experience is a constellation of notes. Monochrome cards and violet connections open into focused text, so the motion helps orientation instead of competing with it.

## What I built

- Notes organised around decisions rather than news frequency
- A clear context, option and outcome pattern for technical writing
- Constellation navigation with ordinary links underneath
- Nine Serbian and nine English canonical routes
- Readable typography, keyboard focus and reduced-motion support

## Release checks

Every canonical route was checked at 390, 768, 1440 and 1920 px. The release was also tested without JavaScript and with reduced motion. Live checks covered HTTPS, redirects, response headers, structured data, sitemap files, protected paths and invalid contact requests without sending test mail.

These are engineering checks, not claims about search ranking or field performance.

---

<sub>Designed and built by [D. Svilenković](https://svilenkovic.com).</sub>
