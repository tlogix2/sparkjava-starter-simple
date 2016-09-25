![](https://img.shields.io/travis/thoughtlogix/sparkjava-starter-simple.svg) 
![](https://img.shields.io/github/license/thoughtlogix/sparkjava-starter-simple.svg)

# Sparkjava Simple Starter

The sparkjava simple starter provides a basic seed or example project using Spark, Kotlin and Gradle.  While it demonstrates basic routing, error handling and templates, it will not do much more than that.  Database integration, mail notifications, authentication will be used in the [SparkJava Advanced Starter](https://github.com/thoughtlogix/sparkjava-starter-advanced) project.

## Features and Limitations

* Includes pages for simple routes (home, about, features, etc)
* Adds simple before filters (cors, logging, sessions, etc)
* Uses Pebble for templates with basics features (inheritance, partials, etc)

## Installation

Make sure you have jdk 1.8+ installed.

* Download or clone this repo: `git clone https://github.com/thoughtlogix/sparkjava-starter-simple`.

## Running

From the project dir, run:

* `gradle runServer`

## See also

* [SparkJava Advanced Starter Kit](https://github.com/thoughtlogix/sparkjava-starter-advanced)

## Todo

Until we move into issues for long term use:
 
* Add versioning
* Set values from ENV, args and settings
* Add basic forms
* Add tests
* Add CI
* Maybe add DI
* Add VirtBox & Container
* Add easily replaced placeholders, maybe move to cookiecutter or Yeoman tool.

## Notes

* Not everything is idiomatic Kotlin but we'll get there.

## License

MIT - Go nuts
