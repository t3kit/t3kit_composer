# Testing t3kit with composer
### t3kit with composer.json and without git submodules.

### Getting Started:

- `git clone https://github.com/t3kit/t3kit_composer.git`
- `cd t3kit_composer`

There is two options for installing composer.

1. I want to have the latest stable release from TYPO3:s extension repository:
- `composer install --no-dev`

2. The second option is I want to develop and contribute then use the following install command:
- `composer install`

### Or if you want to install t3kit with predefined database using [Vagrant](https://github.com/t3kit/t3kit_vagrant):

- `git clone https://github.com/t3kit/t3kit_vagrant.git`
- `cd t3kit_vagrant`
- `./initWithComposer.sh`
- `vagrant up`
- open in browser: `localhost:8081`
