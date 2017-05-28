# What is this?

As indicated by the name, this is a simple workflow to create screenshots. It has no functionality beyond that offered by built-in MacOS tools; its only purpose is to save you (well, *me* really, but if you find it useful that's cool too) from having to remember the hotkeys you assigned to screenshot handling.

That means look elsewhere if you want:

* Dropbox integration of any kind
* Uploading screenshots to any service anywhere
* Any functionality pertaining to managing your screenshots

# How do I use it?

* Modify the workflow environment variables to point SCREENSHOT_DIR at the directory you want to use. Unfortunately the `~` shortcut for a home directory doesn't seem to work, so you have to use the full path. The workflow will create the directory if it doesn't exist (and if it has permission to).
* Use the `ss` keyword to take a screenshot as a file, or `ssc` to place a screenshot in the clipboard. The argument will be used as the file name for `ss`, and ignored for `ssc`.
* By default the workflow will capture the whole screen. Use the following modifier keys for different screenshot types:
    * Ctrl: select a rectangle
    * Option/Alt: select a window

# Competitors

If this workflow doesn't have enough functionality for you, here are some others:

* [Screenshots](http://www.packal.org/workflow/screenshots): Very featureful, but might not work with recent versions of Alfred/MacOS. I stole the `ss` keyword from this workflow.
* [Simple Screen Capture](http://www.packal.org/workflow/simple-screen-capture): Even fewer features than this workflow.
* [Screencapture Enhancer](http://www.packal.org/workflow/screencapture-enhancer): Also basic, but with the ability to re-capture the same rectangle repeatedly, which is cool.
* [clipbox](http://www.packal.org/workflow/clipbox): Sends screenshots to Trello, which I guess someone somewhere might want to do?
* [alfred-screen-capture](https://github.com/ginfuru/alfred-screen-capture): Similar minimal feature set to this workflow, but different interface: uses keyword arguments instead of modifiers to select screenshot type, with the tradeoff that it's not as easy to choose the name for each screenshot.
