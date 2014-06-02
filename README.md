# Citrus Designs Website
---
## Development
### Prerequisites
- nodejs and yeoman

---

(you need not run anything of the commands under "development" section. Its like a simple log for debugging)

---
<b>*Note: The project is in "app" folder*</b>

### Initializing (needn't run these)
- yo webapp
- bower install angular
- bower install foundation
- grunt bowerInstall [adds the above two script files to index.html. Files are in bower-components]

## Preview (while developing)
  <b>grunt serve </b> to start preview (auto updates) in browser

## Building
 run <b>grunt</b> to test the project and build it (into "dist" folder)

 <b><i> Note: The "dist" folder is not included in this repo. It is gitignored </i></b>

## Bugs

- [FIXED] imagemin item from Gruntfile.js is screwed up
