# SHare Your Mind 

A companion program for VYM.

:warning: __It is a EARLY STAGE project, do not use for production__


## Early roadmap

### v0.x

* Use cobra / vyper to parse command line options
* Use vymad Go code related to Vym (?)
* Convert to internal tree representation
* Convert richtext (option `--no-richtext`) to simple text
* Export as simple text tree (id + titles only, without notes)
* Export to markdown files
  * Escape mardown content from node names and richtext (option `--no-escape`)
  * Export either to bullet-points (`*`) or to headings depending on subtree depth

## v1.x

* Split into multiple files at given depth (options `--split` and `--split-depth`)
* Export to/Import from JSON files (options `--from-format` and `--to-format`)
* Export to Vym files (options `--from-format` and `--to-format`)
* Add shell completion for bash & zsh

