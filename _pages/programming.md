---
layout: page
permalink: /programming/
title: programming
description: Statistical programming tools, interfaces, and other software I build.
nav: true
nav_order: 3
---

## Rungs

**A weekly task tracker built around a priority ladder.**

Rungs is a local, zero-dependency task tracker for one person. Tasks sit on a
single ordered list for the current Monday–Sunday week: type a task with an
optional deadline shorthand ("Send invoice fri"), check it off when it is
done, and drag rows up and down as priorities shift. Deadline chips are
colour-tiered, completed tasks fall into a weekly diary and archive, and every
action is undoable. It runs from a single folder of plain HTML, CSS and
JavaScript and keeps its data in the browser's local storage. It also comes
as a native Mac app — a small AppKit and WebKit shell around the same files,
built from one Swift source file with no Electron and no packages.

I built it with Claude Code.

**HTML · CSS · JavaScript · Swift (macOS app)**

<p>
  <a class="btn btn-sm z-depth-0" role="button" href="https://muzhi-liu.com/rungs/">View demo</a>
  <a class="btn btn-sm z-depth-0" role="button" href="https://github.com/muzhi-liu/rungs">Source code</a>
  <a class="btn btn-sm z-depth-0" role="button" href="https://github.com/muzhi-liu/rungs/releases/latest">Download for Mac</a>
</p>

---

## Back to Work

**A browser extension that counts how often you check your brokerage account.**

Back to Work is a small Chrome extension for anyone who looks at Robinhood
more often than the market moves. Each time the Robinhood tab comes into view
it adds one to the day's tally and slides in a short, see-through note at the
bottom of the page ("Check #7 today. Staring doesn't make it go up. We
checked."). The note fades after five seconds, lets clicks pass straight
through it, and gets less patient as the count climbs. The toolbar button
shows today's count and the past week, with a switch that pauses everything.
It asks for a single permission, keeps its tally in the browser's local
storage, reads nothing from the page and sends nothing anywhere. It is an
independent project, not affiliated with Robinhood, and it is not on the
Chrome Web Store: unzip the download and load the folder from
`chrome://extensions` with Developer mode switched on.

I built it with Claude Code.

**JavaScript · HTML · CSS (Chrome extension, Manifest V3)**

<p>
  <a class="btn btn-sm z-depth-0" role="button" href="{{ '/assets/zip/back-to-work.zip' | relative_url }}" download="back-to-work.zip">Download (.zip)</a>
</p>

---

More programs will appear on this page as they are released.
