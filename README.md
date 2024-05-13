# 🍲 Cookbook 📖

<div align="center">
    <a href="https://pi-etro.github.io/cookbook/_site/index.html">https://pi-etro.github.io/cookbook</a>
</div>
<br>

My recipe collection for personal use and for sharing with family and friends!


Built with [nyum](https://github.com/doersino/nyum), the "**cookbook for nerds**" static site generator. 

## Usage

### Setup

Install the only dependency:

* [Pandoc](https://pandoc.org) – version 2.8 (released in November 2019) or later

For macOS, `brew install pandoc` will do the trick. On Linux, your package manager almost certainly has it (although the version it provides might be outdated – recent binaries are available [here](https://github.com/jgm/pandoc/releases/latest)).

(If you're a Windows user, setup the [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) to run the build.sh)

### Building

Run `./build.sh` and open with your browser the html generated in the `_site` folder.

### Deployment

The deployment is done via GitHub action (see `.github/workflows/build-ci.yml`), it instantiate a Ubuntu system, install a recent version of Pandoc, build the site, and deploy it to the `gh-pages` branch of the repository.

## License

You may use this repository's contents under the terms of the *MIT License*, see `LICENSE`.

However, the subdirectories `_assets/fonts/` and `_assets/tabler-icons` contain **third-party software with its own licenses**.
