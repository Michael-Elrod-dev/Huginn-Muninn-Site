# Huginn-Muninn-Site

The public web presence for [Huginn & Muninn](https://github.com/Michael-Elrod-dev/Huginn-Muninn),
a personal daily-briefing and reminder system.

Two static pages, served by GitHub Pages at **huginn.michaelelrod.dev**:

| Path | What |
|---|---|
| `/` | what the application is and who it is for |
| `/privacy/` | the privacy policy |

Both exist because Google requires a reachable homepage and privacy-policy URL before an
OAuth consent screen can leave *Testing* status — and in Testing, Google expires refresh
tokens after seven days, which silently broke the calendar integration.

Deliberately plain HTML with no build step, no dependencies and no framework. It should
still serve correctly, untouched, in ten years.
