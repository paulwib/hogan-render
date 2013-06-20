#hogan-render

A little wrapper to render hogan templates at the command line.
Use it like: `hogan-render <mustache template file> <json data file>` e.g.

  hogan-render template.mustache data.json

Alternatively data can be read from STDIN e.g.

    cat data.json | hogan-render template.mustache

You can also run with just a template and type data at stdin
Use Ctrl+D (i.e. EOF) to have the data rendered
