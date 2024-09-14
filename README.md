Guess My RGB
============

*Guess My RGB* is a tiny, web-based, colour guessing game.  The game
is available as a single HTML page that runs in a web browser.  It
presents a page with a randomly chosen background colour.  Your job is
to guess the three RGB hexademical digits that make the given
background colour.

[![Screenshot of a completed game of Guess My RGB][IMG1]][PLAY1]

**[PLAY NOW!][PLAY1]**

[PLAY1]: https://susam.net/myrgb.html
[IMG1]: https://susam.github.io/blob/img/myrgb/myrgb-0.1.0.png


Contents
--------

* [Play](#play)
* [License](#license)
* [Support](#support)
* [See Also](#see-also)


Play
----

The current stable version of this game is available at the following
links:

* [susam.net/myrgb.html][PLAY1]
* [susam.github.io/myrgb.html][PLAY2]

You can also play the game in *expert mode* by clicking on the "Mode"
link in the footer or by adding `#x` to the URL like this:

* [susam.net/myrgb.html#x][PLAY4]
* [susam.github.io/myrgb.html#x][PLAY5]

While playing in expert mode the match percentage for your guess is
not displayed.

[PLAY1]: https://susam.net/myrgb.html
[PLAY2]: https://susam.github.io/myrgb.html
[PLAY3]: https://susam.github.io/myrgb/myrgb.html

[PLAY4]: https://susam.net/myrgb.html#x
[PLAY5]: https://susam.github.io/myrgb.html#x
[PLAY6]: https://susam.github.io/myrgb/myrgb.html#x


License
-------

This is free and open source software.  You can use, copy, modify,
merge, publish, distribute, sublicense, and/or sell copies of it,
under the terms of the MIT License. See [LICENSE.md][L] for details.

This software is provided "AS IS", WITHOUT WARRANTY OF ANY KIND,
express or implied. See [LICENSE.md][L] for details.

[L]: LICENSE.md


Support
-------

To report bugs or ask questions, [create issues][ISSUES].

[ISSUES]: https://github.com/susam/myrgb/issues


See Also
--------

See [Andromeda Invaders](https://github.com/susam/invaders), a
1980s-arcade-style game written using HTML5, Canvas, and Web Audio.

See [CFRS[]](https://github.com/susam/cfrs), an extremely minimal
turtle graphics language with only 6 simple commands.

See [FXYT](https://github.com/susam/fxyt), a tiny, stack-based,
postfix, canvas colouring language with only 36 simple commands.

<!--
Release Checklist
-----------------

- Update version in package.json.
- Update version in HTML (1 place).
- Update copyright in HTML (1 place).
- Update copyright in LICENSE.md.
- Disable logging.
- Update CHANGES.md.
- Run the following commands:

  npm run lint
  git status
  git add -p

  VER=<VERSION>
  git commit -em "Set version to $VER"
  git tag $VERSION -m "Guess My RGB $VER"
  git push origin main $VERSION

  git remote add cb https://codeberg.org/susam/myrgb.git
  git push cb --all
  git push cb --tags


Screenshot
----------

- Set web browser size to 1600x1200.
- Go to web browser console and enter: setGame(15, 12, 9)
- Enter: 776, 996, C96, FC9
-->
