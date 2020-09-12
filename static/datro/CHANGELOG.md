# Changelog
It's expected that developers log all changes to this directory, in this CHANGELOG.md file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

### static/datro - version 0.0.1
This version ID is for this specific directory - for reference purposes only.
The actual semantic version is below - with the extension 'RTW' which represents this repositories branch.
For more info about semantic version control and our use of bespoke extensions, read the top-level COLLABORATE.md file.
## [Unreleased]

## [0.0.1-rtw.8] - 2020-09-03

### /static/datro - version 0.1

### Added
    - GNU General Public Licence - sitewide
    - local boostrap-grid.css, or else the columbs turn into rows if the cdn bootstrap isn't reachable.   

### Changed
    - Changed `href="#myCarousel"` to `data-target="#myCarousel"` on the splashpage, to fix a bug (page was scrolling)
    - html theme now matches website theme

### Removed
    - <link href="https://www.f-cdn.com/assets/bundles/jquery-4df54fac.js" rel="preload"> appeared multiple times on the same page.
    - modernizer.js is discontinued, not the service, just the single js file method. So it's been removed, since it was causing errors.
    - removed videolightning.js too, haven't used that feature for a while.

### Fixed
    - The frame the docs are displayed in (featherlight) was scrolling upwards off screen, whenever you selected the doc. Fixed it!
    - Copyleft symbol wasn't appearing on chrome on android. Reversed copyright symbol using css instead.
    - changed background color to theme, the white default was making the website look poor between page refreshes

### To Do
    - The dropdown in the footers seems to work locally now, let's see if it works when the sites pushed to gh-pages .... No :(

### Issues

## [0.0.1-rtw.7] - 2020-06-24
### Added

### Changed

### Removed

### Fixed

### Issues