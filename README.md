# Intro to Git and GitHub

An introductory slide deck about version control with Git and collaboration
through GitHub. It covers installation and configuration, repositories,
staging changes, diffs, commits, version history, and pushing and pulling.

Created by Aris Paschalidis for educational use while a member of the Bailey
Lab at Brown University.

## View the presentation

View the presentation at
[arisp99.github.io/git-and-github](https://arisp99.github.io/git-and-github/).

## Render from source

Install [Quarto](https://quarto.org/docs/get-started/), then run:

```bash
quarto render git-and-github.qmd
```

This regenerates the presentation from [`git-and-github.qmd`](git-and-github.qmd).
The R snippets in the slides are displayed examples; running them requires R
and the [`usethis`](https://usethis.r-lib.org/) package.

Changes pushed to `main` are automatically published to GitHub Pages by the
repository's GitHub Actions workflow.

## License

Except where otherwise noted, this project is licensed under the
[Creative Commons Attribution 4.0 International License](LICENSE). You may
share and adapt the material with appropriate credit.
