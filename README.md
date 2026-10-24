# portfolio-v2

The second version of my personal site. I'm Jayden, an IT and security person based in Melbourne, and this is where I tell the story of how I got here: from Malaysia, through a lot of kitchens and retail floors, to running IT for a crypto brokerage.

Live site: https://zchean1216.github.io/portfolio-v2/

## How it was made

I wrote the content and decided how the site should look and feel: the five-chapter story, the git-commit timeline, the space theme and the jokes. I built it with help from AI (Claude Code), which did a lot of the heavy lifting on the animation code and layout. I know that's not the same as writing every line myself, and I'd rather say so up front.

## What's in it

- Plain HTML, CSS and vanilla JS. No framework, no build step.
- Space-themed animations: asteroid field, star field, comets, a rocket loading screen.
- Light and dark mode, a custom cursor, scroll reveals, and a reduced-motion fallback.
- `js/runtime.js` is a bundled runtime from the tool the layout came from, so it isn't hand-written.

## Running it locally

    python3 -m http.server

Then open http://localhost:8000. Fonts come from Google Fonts, so you need a connection.
