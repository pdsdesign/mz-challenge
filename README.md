<<<<<<< HEAD
# [Foundation for Sites](http://foundation.zurb.com)

[![npm version](https://badge.fury.io/js/foundation-sites.svg)](https://badge.fury.io/js/foundation-sites) [![Bower version](https://badge.fury.io/bo/foundation-sites.svg)](https://badge.fury.io/bo/foundation-sites) [![Gem Version](https://badge.fury.io/rb/foundation-rails.svg)](https://badge.fury.io/rb/foundation-rails) [![devDependency Status](https://david-dm.org/zurb/foundation-sites/dev-status.svg)](https://david-dm.org/zurb/foundation-sites#info=devDependencies) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/zurb/foundation-sites?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Foundation is the most advanced responsive front-end framework in the world. Quickly go from prototype to production, building sites or apps that work on any kind of device with Foundation. Includes a fully customizable, responsive grid, a large library of Sass mixins, commonly used JavaScript plugins, and full accessibility support...

## Getting Started

The quickest way to get started is with the [basic CSS download](http://foundation.zurb.com/sites/download/). You can get versions with every component, essential ones only, or a custom build.

If you're a Sass user, we have two starter project templates, the [Basic Template](https://github.com/zurb/foundation-sites-template) and the [ZURB Template](https://github.com/zurb/foundation-zurb-template). You can install them by manually downloading them from GitHub, or using the [Foundation CLI](https://github.com/zurb/foundation-cli).

Lastly, if you're rolling your own setup, you can install Foundation through a variety of [package managers](http://foundation.zurb.com/sites/docs/installation.html#package-managers).

## Documentation

The documentation can be found at <https://foundation.zurb.com/sites/docs>. To run the documentation locally on your machine, you need [Node.js](https://nodejs.org/en/) and [Ruby](https://www.ruby-lang.org/en/) installed on your computer.

Run these commands to set up the documentation:

```bash
git clone https://github.com/zurb/foundation-sites
cd foundation-sites
gem install scss-lint
npm install
```

Then run `npm start` to compile the documentation. When it finishes, a new browser window will open pointing to a BrowserSync server displaying the documentation.

## Contributing

Check out our [contributing guide](http://foundation.zurb.com/develop/contribute.html) to learn how you can contribute to Foundation. You can also browse the [Help Wanted](https://github.com/zurb/foundation-sites/labels/help%20wanted) tag in our issue tracker to find things to do.

Copyright (c) 2016 ZURB, inc.
=======
# Foundation for Sites Template

**Please open all issues with this template on the main [Foundation for Sites](https://github.com/zurb/foundation-sites/issues) repo.**

This is the basic starter project for [Foundation for Sites 6](http://foundation.zurb.com/sites). It includes a Sass compiler and a starter HTML file for you.

## Installation

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

This template can be installed with the Foundation CLI, or downloaded and set up manually.

### Using the CLI

Install the Foundation CLI with this command:

```bash
npm install foundation-cli --global
```

Use this command to set up a blank Foundation for Sites project with this template:

```bash
foundation new --framework sites --template basic
```

The CLI will prompt you to give your project a name. The template will be downloaded into a folder with this name.

### Manual Setup

To manually set up the template, first download it with Git:

```bash
git clone https://github.com/zurb/foundation-sites-template projectname
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
bower install
```

Finally, run `npm start` to run the Sass compiler. It will re-run every time you save a Sass file.
>>>>>>> b46ae9c42d18c401002d4553ab16a76ad40cc996
