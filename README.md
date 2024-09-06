# Practicing Staff+ Principles in Open Source

This talk was presented at [StaffPlus New York 2024](https://leaddev.com/staffplus-new-york).

The slides were built using [Marp](https://marp.app/), a Markdown to slide deck framework. It uses the [Rose Pine Dawn theme](https://rnd195.github.io/marp-community-themes/theme/rose-pine-dawn.html).

## Local development

The quickest way to get started if you don't have Node.js or the [`marp` CLI](https://npm.im/@marp-team/marp-cli) installed is to use [`mise`](https://mise.jdx.dev/getting-started.html).
Once that is set up:

- Run `mise install` in the project directory
- Run `mise run dev` to build the slides as HTML, open a preview window, and watch for changes

If you don't want to use `mise`, manually install the [`marp` CLI](https://npm.im/@marp-team/marp-cli) using your preferred JavaScript package manager. 
Once that is set up, run

```console
marp -w presentation.md -o build/presentation.html --theme-set ./themes -p
```
