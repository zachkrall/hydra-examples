# An Introduction to Hydra

## What is Hydra
Hydra is a live-coding library created by [Olivia Jack](https://github.com/ojack). While Hydra uses JavaScript, it is structured in a way that requires little intimate knowledge of JavaScript. If you are coming from another language, or are new to programming, you can build really interesting visuals in Hydra.

Essentially, Hydra takes an input → modifies it → and returns an output.

## Installing Hydra

There are three options for getting Hydra onto your computer. I recommend starting with the online editor before downloading the Atom package.

**Using a Web Browser:**
* Navigate to [https://hydra-editor.glitch.me](https://hydra-editor.glitch.me).
* ✨ You're ready! ✨

**Using Atom:**
* Download and install [Atom](https://atom.io), an open source text editor built by GitHub.
* Install inside Atom:
  * Open _Preferences_
  * Click _Install_ on left sidebar
  * Search for "atom-hydra" using search bar and click install
  * Restart atom editor
* Install using APM (Atom Package Manager):
  * The Atom Package Manager is a Command Line tool that you can use to install atom plugins
  * Open terminal
  * Run `apm install atom-hydra`

To start Hydra inside Atom, click _Packages_ in top menu bar. Under "atom-hydra" select _Toggle_. Press _Control_ + _Option_ + _Enter_ to evaluate a block of code.

**Running Locally (Requires Node):**
* Open _Terminal_
* Run `git clone https://github.com/ojack/hydra`
* Run `cd hydra` to move into newly created hydra directory
* Install dependencies by running `npm install`
* Start local server by running `npm start`

--------------

# Examples

To follow along with slides, use example files found in [examples](/examples)

--------------

# Cheatsheet

[List of all available function](https://github.com/ojack/hydra/blob/master/docs/funcs.md)

## Variables & Functions

|name |description |example |
|:-|:-|:-|
| bpm | change bpm of hydra cycles | `bpm( 120 );` |
| Math.abs | keep values position | `Math.abs(-1) // returns 1` |
| Math.random | creates a random float between 0 and 1 | `Math.random()*2` |
| Math.sin | sin wave for more fluid animation | `Math.sin(value)` |
| mouse.x | x position of mouse | `mouse.x / window.innerWidth * 100` |
| mouse.y | y position of mouse | `mouse.y / window.innerHeight * 100` |
| time | elapse time in milliseconds | `() => Math.sin(time)` |
| window.innerWidth | width of window | |
| window.innerHeight | height of window | |
| screencap | eval this function to save an image of your hydra sketch | `screencap();` |

----------
