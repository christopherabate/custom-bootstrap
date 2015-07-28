# custom-less-bootstrap
Template for custom LESS Twitter Bootstrap

## Quick start

1. Two quick start options:

- [Download the master branch](https://github.com/christopherabate/custom-less-bootstrap/archive/master.zip).
- Clone the repository: `git clone https://github.com/christopherabate/custom-less-bootstrap.git` under your project name (ex. `my-project`).

2. Replace every occurence of `custom-less-bootstrap` by `my-project` in [package.json](./package.json), [bower.json](./bower.json) and [index.html](./index.html).

3. Install Node modules with `npm install`.

4. Install Bower components with `npm-exec bower install`.

## Customization
 
1. Modify [less/custom-bootstrap.less](./less/custom-bootstrap.less) or/and [less/custom-variables.less](./less/custom-variables.less).
2. Run `npm-exec grunt` to generate a distribution.
3. Open [index.html](./index.html) to see the results.
