# Advent-Toolbox
Advent of code toolset.

## Motivation

The motivation for this project comes from simple boredom and QOL for the 2023 AOC.

Since I'll be participating in the 2023 AOC I needed something to manage my days and years.

With so many years and challenges it's a bit overwhelming with a bunch of different ways to manage.

I decided a CLI/TUI/GUI approach to this problem is perfect to hide the backend workspaces.
Each "day" will get it's own entire workspace keeping challenges as streamlined as possible.

## Language Choice

The desktop application will be written in rust. I will provide downloads and install scripts
for those not inclined to compile and run this themselves.

I plan on keeping this platform-independent, meaning all platforms can benefit from this toolset.

The CLI portion will be a more reliable use of this project, and the GUI will have secondary
level maintenance non-preferred to the CLI.

Ideally any language can be used to solve advent of code, I personally use rust so basing the
entire project off rust makes it a bit more simple to interface with any new projects and creates
parody with the provided toolbox library which will be provided to rust users.

Any additionally added languages will not have the `advent-toolbox-lib` but one could be created
for other languages and inlayed into the template for those inclined.

## To Do

- [ ] Setup authentication control
- [ ] Automate challenge retrieval
- [ ] Integrate basic templating
- [ ] Automate folder control flow
- [ ] Integrate puzzle input "types" and resolvers
- [ ] Integrate puzzle output "types" and ingestors
- [ ] Create advent-toolbox-lib crate which can be used as an extension to speed up challenge solving
- [ ] Add method for inserting test cases & run test cases using the cargo testing framework
- [ ] Add command to automatically pass in a "solution" and display any feedback displayed
- [ ] Integrate rust-based templating setup
- [ ] Integrate template extension to add globally dependant files such as vscode and
      potentially more metadata regarding this project
- [ ] Add project management system for dependant crates per-day
- [ ] Integrate into CLI into GUI along with other parts of the project
- [ ] Inlay AOC description windows into a sub-component of the display to avoid any browser usage
- [ ] Potentially add scraping tools using AI to automate test entry
- [ ] Add more languages and write contributing docs to add new languages
