# Setup

## 1. 3D contribution graph

The README uses:

`./profile-3d-contrib/profile-green-animate.svg`

Go to **Actions → GitHub-Profile-3D-Contrib → Run workflow** once.

The workflow then generates the `profile-3d-contrib` images and commits them to the repository.

## 2. Contribution snake

Go to **Actions → Generate Contribution Snake → Run workflow** once.

The workflow publishes these files to the `output` branch:

- `github-contribution-grid-snake.svg`
- `github-contribution-grid-snake-dark.svg`

The README already references the correct `Syedjunaid23/Syedjunaid23/output/...` paths.

Both workflows then update automatically on their schedules.
