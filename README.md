
## What is SILE?

SILE is a typesetting system. Its job is to produce beautiful printed documents. It’s similar to TeX, but with some ideas borrowed from InDesign, and written with modern technologies in mind.

## What can I do with it (that I can’t do with TeX)?

SILE allows you to

* Produce complex document layouts using frames.

* Easily extend the typesetting system in a high-level programming language. (Lua)

* Directly process XML to PDF without the use of XSL stylesheets.

* Typeset text on a grid.

## Getting and installing

SILE can be downloaded from [its home page][1], or directly from [the release page][2].

SILE is written in the Lua programming language, so you will need a Lua version 5.1 installation; it also relies on the Cairo and Pango libraries.

You also need to install the following Lua libraries using [luarocks][] (downloading luarocks if you do not already have it installed).

* `stdlib`
* `lgi` 
* `lpeg` 
* `luaexpat`
* `inspect`
* `luaepnf`
* `luarepl`
* `cassowary`

Once your dependencies are installed, run

* `lua install.lua`

This will place the SILE libraries and executable in a sensible location.

Now try `sile examples/test.sil`.

## Finding out more

Please read the [full SILE manual][3] for more information about what SILE is and how it can help you.

## Contact

Please report bugs and send patches and pull requests at the [github repository][4]. For questions, please contact the author, Simon Cozens <simon@simon-cozens.org>.

## License terms

SILE is distributed under the [MIT licence][5].

[1]: http://www.sile-typesetter.org/ 
[2]: https://github.com/simoncozens/sile/releases
[3]: https://raw.githubusercontent.com/simoncozens/sile/master/documentation/sile.pdf
[4]: https://github.com/simoncozens/sile
[5]: http://choosealicense.com/licenses/mit/
[roadmap]: https://github.com/simoncozens/sile/blob/master/ROADMAP
[luarocks]: http://luarocks.org/en/Download
