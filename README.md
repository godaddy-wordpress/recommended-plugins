# GoDaddy WordPress Recommended Plugins #

Manifest of all WordPress Plugins recommended by GoDaddy.

### How to update

1. Clone this repo
2. Run `cp pre-commit .git/hooks/pre-commit` (Copies the pre-commit file to the appropriate directory)
3. Run `git checkout develop` and **ONLY** make changes to `recommended-plugins.json`
4. Commit your changes (minification of `recommended-plugins.json` will run automatically)
5. Do a `git push`
6. Issue a PR against `master` (requires peer approval to merge)
