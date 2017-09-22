---
# Headless Testing
---
# A Simple Console App
- Simple Tests
- Side Effects limited to console read/write
- Streams
---
# JavaFX
- Big UI Framework
- Can be tested with TestFX (a testing framework)
---
# Continuous Integration
- No UI to test against
- What to do with UI tests?
---
# Three options
- Don't test UI
- Only run locally
- Headless testing
---
# Monocle
- "provides windowing functionality and access to native graphics for simple embedded systems that do not have an underlying window system"
- `gradle -Pheadless=true test`
- Adding .travis.yml configuration
---
# More relevant example
- DOM testing
- PhantomJS (old version of JavaScript)
- Chrome Headless (since April 2017)
- Node/jsdom
---
