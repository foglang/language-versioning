# Version 0 (Printing)
FOG version 0 allows for printing data to console. This version also includes support for comments, but comments aren't bound to a specific tag.

## Supported tags
* `<u>`
* `<pre>` (*)

## Note on `<pre>`
The `<pre>` tag is not bound to a specific version and a compiler can be compliant without suporting it. This is due to the fact that some of the lanaguages FOG compiles to have no support for arbirary unicode characters and instead of converting them, a developer may opt to remove `<pre>` support. Support of rich-text and the pre tag can be indicated by adding `-rich` to the language version code, this is **not** required. When `<pre>` tags are not supported, it is expected that the compiler would produce an error when they are encountered as to reduce undefined behavior.
