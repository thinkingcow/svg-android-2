# Purpose #

Provide a place to contribute enhancements to the svg-android project


# Roadmap #

  1. Add missing Svg capabilities to the library for the purpose of supporting Inkscape output, while maintaining the original program structure.
  1. Provide a simple Android "Test" app to exersize and test the library.
  1. Restructure the library to enable correct SVG parsing (e.g maintain a stack of Paint properties).
  1. Keep an AST of the current SVG to allow efficient and interactive manipulation of SVG images.

# Status #

Many capabilities have been added to the library while conforming to
its existing structure, including:
  * support transforms in **g** tags
  * support transform lists (e.g. transform="rotate(..) scale(..) ...")
  * support for arcs in paths
  * support implied commands in paths
  * support for named colors
  * support for text (limited, but including font-size, type-face, and text alignment)
  * support for stroke-dasharray for dotted/dashed lines


# Rational #

I submitted a patch to the svg-android project a more than 2 months
ago, and contacted the owners of the project out of band, but have not
received a response.  I would like to share the enhancements I've made
to this project with the community, but since the owners of the project are either unable or unwilling to accept them, I'm making them available
here.