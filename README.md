# pngdeer demo

A tiny project that shows [oxlint-plugin-pngdeer](https://github.com/lndgalante/oxlint-plugin-pngdeer) on a pull request. It uses the plugin's README setup as is: `.oxlintrc.json` turns the rule on, and [`.github/workflows/images.yml`](.github/workflows/images.yml) lints each pull request with `npx oxlint --format github`.

[Pull request #1](../../pull/1) adds a 509 kB PNG. The check annotates the line that uses it, with how much smaller it could be and the command that shrinks it.
