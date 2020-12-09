# FlexBE CI ![Build Status](https://github.com/flexbe/flexbe_ci/workflows/FlexBE%20CI/badge.svg)

Continuous integration for FlexBE.

## Usage

Copy the file `.travis.yml` into the root folder of your repo.

Substitute

    before_install:
      - ln -s $PWD ~/flexbe_ci
      - source ~/flexbe_ci/setup.bash

by

    before_install:
      - git clone https://github.com/FlexBE/flexbe_ci.git ~/flexbe_ci
      - source ~/flexbe_ci/setup.bash

Happy testing!
