## docco-multidir
Docco-multidir is an improvement over the original docco written by jashkenas (http://jashkenas.github.com/docco/).

Docco-multidir is a dependency of grunt-docco-multi-dir, another new npm module, which is a direct ripoff of grunt-docco-multi and the concept behind grunt-docco-dir.

The purpose of this improvement is to provide better support projects with multiple directories and files.

## Improvements

Modified docco.js & resources/parallel/docco.jst to:
* handle paths for multiple directories
* determine relative path from the output doc html file to the css file 
* accept a new option from the gruntfile for the Project Name
* expose all of the above to the template for use when creating doc files
* update the Jump Menu for proper link pathing


## Known Issues
As of v 1.0.0, only the parallel template uses the new jump menu and output template.


## Github Repo
https://github.com/LareG/docco-multidir.git


## Installation

  sudo npm install -g docco-multidir


## Usage: 
Usage was not modified from the original docco.

docco [options] FILES

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
