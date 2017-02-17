# Majordome

### *(means 'butler' in French)*

## What is it ?

Majordome is a **CSS boilerplate**, containing a set of CSS declarations changing the default aspect of every HTML element to give it a nicer feel.

## Am I supposed to use it ?

**Short answer:** if you're working on a project with a big interface, no. If it's the beginning of a side project, then **yes**

Majordome only gives your website a basic and responsive interface, but as it does not use any CSS class you can't do a mre complex interface ( using things like dropdown menus, etc. ).

This boilerplate is meant to be used at the start of a project, when you don't have the time to develop a little interface but you still want your website to not look too ugly

I don't recommend using it in prod ( it isn't even finished atm, and even when it will be finished I don't recommend using it at a professional level )

## Installation

You can either install Majordome using the default theme or download the source and change some settings ( such as the primary color of the theme, the font, the size, etc. ) using SASS
### 1. Using the default theme

Just download `src/majordome.css` and link it to your website

### 2. Changing the settings

`git clone` the repo

Change the values inside `src/scss/config.scss` to tweak the settings or even change the code of `main.scss` if you want to change a lot of things

Compile using SASS
