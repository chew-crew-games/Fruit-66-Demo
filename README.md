# Fruit-66-Demo
![WebGL Build](https://github.com/chew-crew-games/Fruit-66/actions/workflows/build-webgl.yml/badge.svg)

A chaotic, silly driving and cooking game made for GGDA's Best-In-Georgia Competition 2023.

This game is about you: the proud owner of a new smoothie-slinging food truck.  Unfortunately, staffing is a little tight these days, so you have to do everything yourself -- blending smoothies and delivering the drinks to your en-route customers, all while safely navigating the historic Route 66.

Your objective is to make the most money by delivering orders quickly and accurately, but watch out for other drivers on the road!

# Play it!

This repo hosts the latest WebGL build of our game as a playable demo.

[Click here to play!](https://chew-crew-games.github.io/Fruit-66-Demo/)


## Controls:
- `WASD` to drive the car
- `Click` to pick things up
- `Spacebar` to toggle between "driving" and "throwing" modes

# Updating the build:
The build is updated automatically via Github Actions whenever new releases are created in the main repo.

If you need to perform a manual deployment, you can do the following:
- Download the latest WebGL build from the Github Action in our main repo
- Overwrite everything in the `docs` directory in this repo with the contents of the build.  Usually the resulting files/directories would look something like:
  - `docs/Build`
  - `docs/TemplateData`
  - `docs/index.html`
- Push to overwrite `main`.  That's it.  The Github Action in this repo will automatically deploy it in a minute or so.
