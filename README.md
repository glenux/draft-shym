# SHare Your Mind 

A companion program for [VYM](http://www.insilmaril.de/vym/).

:warning: __It is a VERY EARLY STAGE project, do not use for production__


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


## License and copyright

[Shym](https://github.com/glenux/shym) is an open source project under some OSI license (to be defined)

Author: Glenn Y. Rolland ([@glenux](https://twitter.com/glenux))


## Sponsors and funding

[Shym](https://github.com/glenux/shym) is an independent project whose development and maintenance is made possible thanks to the support of its patrons.

If you wish to join them and support the work of its author, just participate with this link :

&gt;&gt;  __[Become a patron or sponsor on Patreon](https://www.patreon.com/glenux)__ &lt;&lt;

