# svgx
Shell script chaining various SVG optimization tools

Various SVG optimization tools exist, but none of them alone produces the best size
reduction.

svgx will call svgcleaner, scour, and svgo with various parameters in that order to
optimize SVG files.
