# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Single static `index.html` (inline CSS and JS, no build step). Hosted on GitHub Pages at https://joshuadavidcamtugan.github.io/rest-cure/ (repo: joshuadavidcamtugan/rest-cure); an older Vercel deploy also exists.

## Users

Primary: the author's evaluators and visitors, who open the game from a portfolio link. They are not assumed to know the source story. Some will play on campus wifi, so the game must work with restricted networks and without third-party dependencies where possible.

## Product Purpose

Rest Cure is a text-based web game based on Charlotte Perkins Gilman's short story "The Yellow Wallpaper." It makes the player experience the narrator's loss of agency: choices narrow, stats collapse regardless of effort, and the game ends where the story does. As a portfolio piece, success means a visitor plays through, understands the point, and judges the craft of the work.

## Positioning

A game whose mechanics enact the story's argument: the player's actions are slowly replaced by the wallpaper's, and the "treatment" itself drives the decline. Dialogue is taken verbatim from Gilman's text.

## Operating Context

Played in a browser in one sitting. Three stats (Wellness, Energy, Opinion of John), 0–100, shown as bars. Play proceeds through an intro, eight phases and an ending. Phase changes are triggered by specific actions (Write, Write about the wallpaper, repeated counts). An alternate ending sends the player to Dr. Weir Mitchell's sanatorium if Wellness reaches 0 in phases 1–3.

## Capabilities and Constraints

- Source of truth for rules is the author's design document "Rest Cure webgame documentation.docx"; later decisions made in conversation (Energy costs, Weir Mitchell ending, Creep replacing Rest from phase 7) supersede it.
- Dialogue text is from the public-domain story; Beg John lines are verbatim passages supplied by the author.
- Terminology: phases, Normal Actions, Wallpaper Actions, Ending Actions.
- Current look (incumbent, to preserve unless redesigned): dark gray ground, yellow hand-drawn-style mockup layout, stat bars top-left, dialogue and action buttons bottom center, Garamond title and dialogue, Inter for labels and buttons.
- Visual inspiration volunteered by the author: the game SPENT (playspent.org). Not yet recorded as binding; to be interpreted in the design phase.

## Brand Commitments

Title: "Rest Cure." Author-chosen mockup layout (start screen with title and PLAY; gameplay screen with stat bars top-left, dialogue and options at the bottom), yellow-on-dark palette, Garamond for title and dialogue, Inter for stats and options, italic dialogue in a silver tone.

## Evidence on Hand

Full dialogue and rules in the .docx; the two hand-drawn mockups; the live game. No playtest data, no audience metrics, no testimonials.

## Product Principles

- The mechanics are the argument: the interface should never give the player more agency than the story's narrator has.
- Gilman's words are the content; copy is never paraphrased or invented.
- The game must remain playable in one short sitting with no install, account or required network beyond loading the page.
- Craft is judged: details, pacing and feel matter as much as the rules.

## Accessibility & Inclusion

No product-specific standard established. Text must stay readable against every background state, including the fully yellow ending screen and the white Weir Mitchell screen.
