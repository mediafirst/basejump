# Basejump WordPress theme

## Introduction

Some people swear by frameworks, some of us work best with grids and yet others prefer to build child themes off the WordPress default theme(s).

Having worked with all of the above, they have one thing in common: there's always something.

* A framework tends to try to cover all its bases and is therefore by default adding way too much "fluff" to the equation.
* When developing based on a grid - whether it's 12 columns, 16 columns, the golden ratio or whatever - there comes a point that a design is just that bit different and you will need to introduce all kinds of div's and/or classes to make the design fit the grid.
* Child themes are nice most of the times, but you need to rewrite a lot of functions or you're stuck with code that never gets used; in other words you'll end up with unnecessary overhead. 

That has been the main reason for me to develop this Basejump WordPress theme.

With the name I have tried to already suggest what it is. Take this theme and "jump off a cliff" (not literally of course) to make it into the site you want it to become.

## Features

Although the Basejump WordPress theme is a base theme for you to build upon, it still comes packed with quite a few features and I have coded it for WordPress 3.4 and above.

* Six different Page Templates, neatly organized in their own Page Templates directory (WordPress 3.4 feature)
* Upto six columns (best used on the Full Width Page Template)
* Fully internationalized
* WPML ready and when activated it shows the language menu right in the menu bar navigation
* Custom background with default background when no custom background has been uploaded by the user; coded with add_theme_support (WordPress 3.4 feature)
* Seven "sidebars" including 4 in the footer that can be used for widgets
* Responsive

## Installation

Upload the entire basejump directory to the wp-content folder and activate it through the WordPress Dashboard.

After activation the first thing to do is to add a navigation menu and appoint that menu to be the Primary. Second I suggest to go to the widgets and delete all the widgets that WordPress automatically adds to the first available widget on a fresh install.

Only if you do these two things first, will all the features of the theme work out of the box and will the theme immediately look good.

## FAQ
### Why is the Basejump WordPress Theme not downloadable via the WordPress Theme Repository?

Good question!
Not because I am lazy. The main reason is that I have built the Basejump WordPress Theme with future development (for clients) in mind. Not sure about you, but none of my clients ever has wanted to be able to change the header of the theme. My clients actually want to show their company-logo in the header. One of the requirements of listing a theme in the official WordPress Theme Repository is that you need to have the `add_theme_support('custom-header')` functionality included. As I don't do custom headers the Basejump WordPress Theme therefore cannot be included in the Repository.

### Why does Basejump look so much like the default Genesis child theme?

Fans of Genesis will indeed quickly see that Basejump looks very much like the default Child theme of that premium framework. I actually have tried to work with Genesis, but gave up because to me it is just not a natural way of putting together a website. The reason that my Basejump theme looks so much alike is because I very much like the structure of how the Genesis default child theme has been set up. So I decided to rip it apart and use the structure to base my theme on.

## TODO LIST

To make a default .pot and .po file

## Comments / Questions

You can leave any comments and/or ask any questions on the announcement post on [my website](http://senlinonline.com/2012/06/24/basejump-wordpress-theme/)

## Demo

Actually that should be on the todo list too, but I have used the Basejump WordPress Theme already for a live site that you can see [here](http://senlinhostingclub.com).

## Download (or Fork)
The Basejump WordPress Theme can be downloaded (or forked) from [GitHub](https://github.com/senlin/basejump).

## Disclaimer

The Basejump WordPress theme runs on WordPress version 3.4 and above and I offer no backward compatibility.