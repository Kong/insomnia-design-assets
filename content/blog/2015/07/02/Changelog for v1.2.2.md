This update is mostly under-the-hood changes. Insomnia is now built using babeljs and was refactored to use all of the nice ES6 features. There are also some bug fixes.

### Fixes

- multi window communication broke in Chrome 45 so is disabled for now (was causing the app not to launch)
- import-from-curl is now more robust