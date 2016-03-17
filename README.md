# coopera.github.io

Coopera:lab website

## Instructions

### Setup

To run this website on your local machine, you need to install `ruby`, `jekyll`, `node`, `grunt` and `bower`.

You can install ruby from its [official website](https://www.ruby-lang.org/en/) or installing with a version manager like `rvm` or `rbenv`.

After installing ruby, you need to install a ruby gem called `bundler` and `jekyll`:

```
$ gem install bundler jekyll
```
Then you can install all the ruby dependencies by running `bundle install` from the root.

To install `node`, follow its official website: https://nodejs.org/en/

After have installed `node`, you can install the other dependencies running:

```bash
$ npm install -g grunt-cli bower
$ npm install
$ bower install
```

### Running the server locally

To run the server locally, just run:
```bash
$ grunt serve
```

### How to deploy

To deploy to github pages, just run the following on your terminal:

```bash
$ grunt deploy
```

## Structure

### Projects

All projects are described on the `projects.html`. Feel free to make a Pull Request to update or add new projects.
