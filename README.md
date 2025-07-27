<img src="docs/assets/images/banners/AutoDRIVE Banner.png">

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AutoDRIVE-Ecosystem&label=Views&color=brightgreen">
  <img src="https://img.shields.io/github/followers/AutoDRIVE-Ecosystem?style=flat&label=Followers&color=blueviolet">
  <img src="https://badgen.net/github/stars/Tinker-Twins/AutoDRIVE?label=Stars&color=blue">
  <img src="https://badgen.net/github/forks/Tinker-Twins/AutoDRIVE?label=Forks&color=orange">
  <img alt='GitHub Clones' src='https://img.shields.io/badge/dynamic/json?color=red&label=Clones&query=count&url=https://gist.githubusercontent.com/Tinker-Twins/e2855ef0fa018279b206045be92424cb/raw/clone.json'>
  <img src="https://img.shields.io/github/downloads/Tinker-Twins/AutoDRIVE/total?color=yellow&label=Downloads">
</p>

## Project Overview

<p align="justify">
AutoDRIVE is envisioned to be an integrated platform for autonomous driving research and education. It bridges the gap between software simulation and hardware deployment by providing the AutoDRIVE Simulator and AutoDRIVE Testbed, a well-suited duo for sim2real applications. It also offers AutoDRIVE Devkit, a developer's kit for rapid and flexible development of autonomy algorithms. Although the platform is primarily targeted towards autonomous driving, it also supports the development of smart-city solutions for managing the traffic flow.
</p>

## Branches

- [`main`](https://github.com/AutoDRIVE-Ecosystem/autodrive-ecosystem.github.io/tree/main) contains the source code.
- [`gh-pages`](https://github.com/AutoDRIVE-Ecosystem/autodrive-ecosystem.github.io/tree/gh-pages) hosts the build (deployable) version.

## Workflows

- [`ci`](https://github.com/AutoDRIVE-Ecosystem/autodrive-ecosystem.github.io/actions/workflows/ci.yml) automatically builds the site using MkDocs. It runs automatically after each commit to the `main` branch.
- [`pages-build-deployment`](https://github.com/AutoDRIVE-Ecosystem/autodrive-ecosystem.github.io/actions/workflows/pages/pages-build-deployment) deploys the site. It is called by the `ci` action and runs automatically.

## Deployment

The deployment is live at https://autodrive-ecosystem.github.io
