## docco-multidir

Docco-multidir is (hopefully) an improvement over the original docco written by jashkenas (http://jashkenas.github.com/docco/).

Docco-multidir is meant to be used inconjunction with (and it is a dependency of grunt-docco-multidir), which is a direct ripoff of grunt-docco-multi and the concept behind grunt-docoo-dir.

The purpose of this improvement is to provide better support projects with multiple directories and files.

## Improvements:

Modified docco.js to
* handle paths for multiple directories
* determine relative path from the output doc html file to the css file 
* determine project root name
* expose all of the above to the template for use when creating doc files

Modified resources/parallel/docco.jst
* use relative path for css files
* create a new jump menu with 



https://github.com/LareG/docco-multidir.git


Installation:

  sudo npm install -g docco-multidir




Usage: docco [options] FILES

  Options:

    -h, --help             output usage information
    -V, --version          output the version number
    -l, --layout [layout]  choose a built-in layouts (parallel, linear)
    -c, --css [file]       use a custom css file
    -o, --output [path]    use a custom output path
    -t, --template [file]  use a custom .jst template
    -e, --extension [ext]  use the given file extension for all inputs
    -L, --languages [file] use a custom languages.json
    -m, --marked [file]    use custom marked options
