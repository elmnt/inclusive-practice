# sandbox

A quick local setup to run a local server, and sandbox new ideas. Includes [tachyons-sass](link:https://www.npmjs.com/package/tachyons-sass).  

This uses npm to run everything. I built it to replaec my git-app-dist repo which did the same thing with Gulp.

### Getting Started  

1. `git clone this`
2. cd this
3. `npm install`

The postinstall fires the `npm run dev` command. You'll be serving everything up from the src/ directory. When you're ready to build a production version:
1. `npm run ship`

That's it. Any time you want to clean house and rebuild:
1. `npm run clean && npm run dev`

