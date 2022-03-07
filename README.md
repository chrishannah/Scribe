# Scribe

![hugo version](https://img.shields.io/badge/Hugo-0.91-09f)
![license](https://img.shields.io/github/license/chrishannah/scribe)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat)](https://github.com/prettier/prettier)

A theme for Micro.blog that's a bit more contemporary. Based on my minimal Micro.blog theme, [Fortis](https://github.com/chrishannah/fortis).

## Code Style

This project makes use of the [Prettier](https://prettier.io) code formatter. This formatting will be done automatically in a GitHub Action, but most IDEs can be configured to run this locally.

There is also a second automated step which also runs as part of a GitHub Action, and that is [Super-Linter](https://github.com/github/super-linter). This runs the code through a whole host of linters, and will report any errors. Some configurations have been changed for this project, which can be found under `.github/linters`. The main change is that this project uses tabs instead of spaces.
