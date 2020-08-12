<p align="center">
  <h1 align="center">Laravel Pest - Lucas</h1>
  <p align="center">
    <a href="https://github.com/use-preset/use-preset/releases"><img alt="npx use-preset ycs77/preset-laravel-pest" src="https://img.shields.io/badge/use--preset-laravel--pest-blue?style=flat-square"></a>
    &nbsp;
    <a href="https://www.npmjs.com/package/use-preset"><img alt="use-preset version" src="https://img.shields.io/npm/v/use-preset?color=32c854&style=flat-square&label=use-preset"></a>
  </p>
  <br />
  <p align="center">
    <code>use-preset</code> is a scaffolding tool for developers. <a href="https://docs.usepreset.dev/">Read the documentation</a> for more information.
  </p>
  <br />
  <pre align="center">npx use-preset ycs77/preset-laravel-pest</pre>
  <br />
  <p align="center">See more <a href="https://github.com/ycs77/presets-list">Lucas's Presets</a></p>
<p>

# About

This preset adds [Pest](https://pestphp.com) to a fresh Laravel application.

# Installation

**Run the following command**:

```bash
npx use-preset ycs77/preset-laravel-pest
```

# Usage

Run the test using Pest:

```bash
composer run test
```

# Modifications

This preset follows the [installation instructions](https://pestphp.com/docs/installation/) of Pest by adding `pestphp/pest` and `pestphp/pest-plugin-laravel`, and updating `nunomaduro/collision` and `phpunit/phpunit` to the correct versions. This version add the example test case file for Pest.

It also adds a `test` script to `composer.json` to run `.\vendor\bin\pest`.

Finally, it runs the `pest:install` command.
