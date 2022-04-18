# Metodik
## _A blocks CSS framework_


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Metodik is a CSS framework based on the BEM syntax and on the blocks architecture. It brovides a bunch of css classes and strcutres pre-build.

## Features

- Strong HTML tree structure based on the BEM syntax.
- Build your website with pre-build blocks.
- Customize your website with a custom scss theme file.
- Create custom themes and share them with our community.
- Use our Metodik syntax in your HTML files and simplify your css files
- Much more !!!


## Tech

Metodik uses a number of open source projects to work properly:

- Sass/SCSS!
- Javascript
- HTML5 & CSS3

And of course Metodik itself is open source.

## Installation

Dillinger requires Sass/SCSS (https://sass-lang.com/) to run.

Install the dependencies from the current github and copy/past it on your website folder.

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

## Metodik syntax
Metodik provides a custom syntax based on BEM. You can easily integrate it into your HTML files. Metodik classes are all prefixed with mk- to differentiate them from personal classes that you would add to your project.


Example of a Metodik blocks
```html
<section class="mk-section" id="sectionExample">
    <div class="mk-section__header">
        <div class="mk-box">
            <div class="mk-box__title">
                <h1>Hello</h1>
            </div>
            <div class="mk-box__subtitle">
                <h2>world !</h2>
            </div>
        </div>
    </div>
    <div class="mk-section__body">
        <div class="mk-box --flex-row">
            <div class="mk-box__text">
                <p>Metodik is awsome and I love it !</p>
            </div>
            <div class="mk-box__text">
                <p>With Metodik you can create beautiful websites with very little css code.</p>
            </div>
        </div>
    </div>
    <div class="mk-section__footer">
        <div class="mk-box">
            <div class="mk-box__link">
                <a href="#"> Follow us</a>
            </div>
        </div>
    </div>
</section>
```

## HTML blocks and elements

> Note: All blocks are prefixed by `mk-`.
#### Section
```html
<section class="mk-section" id="sectionExample">
    <div class="mk-section__header"></div>
    <div class="mk-section__body"></div>
    <div class="mk-section__footer"></div>
</section>
```

#### Box
```html
<section class="mk-box" id="sectionExample">
    <div class="mk-box__title"></div>
    <div class="mk-box__subtitle"></div>
    <div class="mk-box__text"></div>
    <div class="mk-box__img"></div>
    <div class="mk-box__thumbnail"></div>
</section>
```

## Modificators
#### Layouts
| Class | Behaviour | Blocks |
| ------ | ------ | ------ |
| `--flex-col`| | |
| `--flex-col-reverse`| | |
| `--flex-row`| | |
| `--flex-row-reverse`| | |
| `--flex-center`| | |
| `--flex-top-center`| | |
| `--flex-bottom-center`| | |
| `--flex-top-left`| | |
| `--flex-top-right`| | |
| `--flex-bottom-left`| | |
| `--flex-bottom-right`| | |

#### Images and thumbnailes
| Class | Behaviour | Blocks |
| ------ | ------ | ------ |
| `--size-smaller`| | |
| `--size-small`| | |
| `--size-medium`| | |
| `--size-large`| | |
| `--size-larger`| | |
| `--size-x-larger`| | |
| `--size-xx-larger`| | |
| `--size-xxx-larger`| | |
| `--size-banner`| | |
| `--ratio-4-3`| | |
| `--ratio-5-3`| | |
| `--ratio-16-9`| | |


## License

Open Source and free

**Free Software, Hell Yeah!**