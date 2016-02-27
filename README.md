# GitHub Dark [![tag](https://img.shields.io/github/tag/StylishThemes/GitHub-Dark.svg)](https://github.com/StylishThemes/GitHub-Dark/tags) [![stars](http://github-svg-buttons.herokuapp.com/star.svg?user=StylishThemes&repo=GitHub-Dark&style=flat&background=007ec6)](http://github.com/StylishThemes/GitHub-Dark) [![forks](http://github-svg-buttons.herokuapp.com/fork.svg?user=StylishThemes&repo=GitHub-Dark&style=flat&background=007ec6)](http://github.com/StylishThemes/GitHub-Dark/fork) [![devdeps](https://img.shields.io/david/dev/StylishThemes/GitHub-Dark.svg)](https://david-dm.org/StylishThemes/GitHub-Dark#info=devDependencies)

Your eyes will :heart: you.

Our dark style includes support for the following GitHub addons:

* [GitHub canned responses](https://github.com/notwaldorf/github-canned-responses#how-to-get-it)
* [Lovely forks](https://github.com/musically-ut/lovely-forks#lovely-forks)
* [Octotree](https://github.com/buunguyen/octotree/#octotree)
* [ZenHub](https://www.zenhub.io/)

## Install

* If using Stylish:
  * Get the Stylish addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/2108/), [Chrome](https://chrome.google.com/extensions/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe), [Opera](https://addons.opera.com/en/extensions/details/stylish/), [Safari](http://sobolev.us/stylish/) and [Firefox Mobile](https://addons.mozilla.org/en-US/firefox/addon/2108/).
  * Then install this style using:
    * [userstyles.org](http://userstyles.org/styles/37035) (with customization options)
    * or, add it [manually](https://raw.githubusercontent.com/StylishThemes/GitHub-Dark/master/github-dark.css) into the editor.
      * Use the [grunt build process](https://github.com/StylishThemes/GitHub-Dark/wiki/Build) to customize your GitHub Dark theme.
      * Please refer to the [installation documentation](https://github.com/StylishThemes/GitHub-Dark/wiki/Install) for more details.
* Or, use our [GitHub-Dark (user)Script](https://github.com/StylishThemes/GitHub-Dark-Script) which requires a [user script addon](https://github.com/StylishThemes/GitHub-Dark-Script/wiki/Install), but allows dynamic style changes & updates:bangbang:

## Preview
![GitHub Dark preview](https://raw.githubusercontent.com/StylishThemes/GitHub-Dark/master/images/screenshots/after_blue.png)

## Available Syntax Highlighting Themes ([Demo](https://stylishthemes.github.io/GitHub-Dark/))

|                 |                      |                        |                          |                       |
|-----------------|----------------------|------------------------|--------------------------|-----------------------|
| Ambiance        | Chaos                | Clouds Midnight        | Cobalt                   | Idle Fingers*         |
| Kr Theme        | Merbivore            | Merbivore Soft         | Mono Industrial          | Mono Industrial Clear |
| Monokai*        | Obsidian*            | Pastel on Dark*        | Solarized Dark*          | Terminal              |
| Tomorrow Night* | Tomorrow Night Blue* | Tomorrow Night Bright* | Tomorrow Night Eigthies* | Twilight*             |
| Vibrant Ink     |                      |                        |                          |                       |

\* Supports [Jupyter notebook syntax highlighting](https://github.com/sujitpal/statlearning-notebooks/blob/master/src/chapter2.ipynb)

## Notes

* If you're using a custom domain for GitHub Enterprise, be sure to include it though a `@-moz-document` rule (Firefox) or add it to the `Applies to` section in (Chrome).
* If you want GitHub commit messages to use a monospaced font, and have a background color indicating the width limits, check out [GitHub Commit Limit](https://github.com/StylishThemes/GitHub-Commit-Limit).

## Contributions

If you would like to contribute to this repository, please...

1. Fork
2. Make changes (please read the [contribution guidelines](https://github.com/StylishThemes/GitHub-Dark/blob/master/CONTRIBUTING.md) and abide by them)
3. Create a pull request!

Thanks to all that have [contributed](https://github.com/StylishThemes/GitHub-Dark/blob/master/AUTHORS) so far!

## Recent Changes

See the [full change log](https://github.com/StylishThemes/GitHub-Dark/wiki).

#### Version 1.14.56 (2/27/2016)

* Readme:
  * Make syntax highlighting demo link more obvious.
  * Fix grammar.
  * Add Obsidian theme to list of available themes.
* Themes:
  * Add Obsidian theme. Fixes [issue #290](https://github.com/StylishThemes/GitHub-Dark/issues/290).
  * Fix class for code type tweaks in various themes. Note: These tweaks currently *only work* on [wiki pages](https://github.com/StylishThemes/GitHub-Dark/wiki/Highlighting). Main files &
    diffs do no include the "highlight-source-..." code type class name (e.g. "highlight-source-css")!

#### Version 1.14.55 (2/24/2016)

* Issues: Fix comment icon on commentless issues.
* Comments:
  * Add toolbar focus color.
  * Add style for a WIP script ;)
* Diff: Tweak red blocks.
* Profiles: Better image crop spinner.
* API: Various fixes.
* Blog: Various fixes.
* Graphs:
  * Fix anonymous site favicons.
  * Fix popular content icons.
* Add support for [github-canned-responses](https://github.com/notwaldorf/github-canned-responses) addon.
* GHD Readme: Reorganized a bit.

#### Version 1.14.54 (2/20/2016)

* Global:
  * Darker green boxes + tweak.
  * Darker red boxes.
* Commits: Fix ellipsis button.
* Discussions:
  * Fix tab colors.
  * Fix lock links.
  * Fix misaligned issue close icon.
* ZenHub + Octotree: Fix expanded boards toolbar position.
