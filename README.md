# Circle

A yearly life plan drawn as concentric rings: a purpose in the centre, then values, aspirations, goals and initiatives. Review it during the year, tick things off, and carry what's unfinished into next year.

## What it does

- **Automatic radial layout.** You edit the content; Circle keeps the structure. Every ring is one level, every value gets its own slice and colour.
- **Keyboard-first editing.** `Tab` adds inside, `Enter` adds next to, `Space` ticks off, typing renames, arrows navigate, `Ctrl+Z` undoes. Drag a card onto another to move it; `Shift`-drag to link it to a second goal it also serves.
- **Three kinds of goal.** Milestones (done or not), numbers with a target, and habits scored by consistency.
- **Reviews.** Quarterly check-ins and a year-end review that walks through every goal, stores a history per card, and ends with your year in numbers.
- **Next year.** Starts a new plan from the current one, carrying over unfinished items and habits.
- **draw.io import.** Reads the structure of an existing `.drawio` mind map, including arrows that weren't attached, and lays it out in rings.
- **Export.** An SVG poster or a JSON backup.

## Running it

It's a single static file with no build step and no dependencies apart from Google Fonts. Open `circle.html` in a browser, or serve it from any static web server.

## Where data is stored

- **Inside claude.ai** (as an Artifact), plans are saved privately to your account and sync across devices.
- **Anywhere else** (a local file or your own server), plans are saved in the browser's `localStorage`. They stay on that one browser and device. Use *Export backup (.json)* to move them, and *Import* to load them elsewhere.
