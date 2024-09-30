# Jekyll runtime dependency metapackages

Provides runtime dependency metapackages for upstream Jekyll installation needs.

<https://gitlab.com/brlin/jekyll-runtime-dependency-metapackages>  
[![The GitLab CI pipeline status badge of the project's `main` branch](https://gitlab.com/brlin/jekyll-runtime-dependency-metapackages/badges/main/pipeline.svg?ignore_skipped=true "Click here to check out the comprehensive status of the GitLab CI pipelines")](https://gitlab.com/brlin/jekyll-runtime-dependency-metapackages/-/pipelines) [![GitHub Actions workflow status badge](https://github.com/brlin-tw/jekyll-runtime-dependency-metapackages/actions/workflows/check-potential-problems.yml/badge.svg "GitHub Actions workflow status")](https://github.com/brlin-tw/jekyll-runtime-dependency-metapackages/actions/workflows/check-potential-problems.yml) [![pre-commit enabled badge](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white "This project uses pre-commit to check potential problems")](https://pre-commit.com/) [![REUSE Specification compliance badge](https://api.reuse.software/badge/gitlab.com/brlin/jekyll-runtime-dependency-metapackages "This project complies to the REUSE specification to decrease software licensing costs")](https://api.reuse.software/info/gitlab.com/brlin/jekyll-runtime-dependency-metapackages)

## Usage

1. Download the respective metapackage that is compatible with your GNU+Linux distribution at [the project's Releases page](https://gitlab.com/brlin/jekyll-runtime-dependency-metapackages/-/releases).
1. Refer to the following sections for distro-specific instructions:

### Debian-based distributions(Ubuntu, Linux Mint)

1. Run the following command _as root_ in a text terminal to ensure your local cache of the package repositories is fresh:

    ```bash
    apt update
    ```

1. Run the following command _as root_ in a text terminal to install the metapackage using your package manager:

    ```bash
    apt install /path/to/jekyll-runtime-deps*.deb
    ```

1. When you no longer need the runtime dependencies you can run the following commands _as root_ in a text terminal to remove the runtime dependency packages:

    ```bash
    apt remove jekyll-runtime-deps
    apt autoremove
    ```

## References

The following material are referenced during the development of this project:

* [Jekyll on Ubuntu | Jekyll • Simple, blog-aware, static sites](https://jekyllrb.com/docs/installation/ubuntu/)  
  Explains how to install Jekyll on Ubuntu using upstream's preferred method.

## Licensing

Unless otherwise noted(individual file's header/[REUSE.toml](REUSE.toml)), this product is licensed under [the 4.0 International version of the Creative Commons Attribution-ShareAlike license](https://creativecommons.org/licenses/by-sa/4.0/), or any of its more recent versions of your preference.

This work complies to [the REUSE Specification](https://reuse.software/spec/), refer the [REUSE - Make licensing easy for everyone](https://reuse.software/) website for info regarding the licensing of this product.
