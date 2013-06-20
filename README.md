#hogan-render

A little wrapper to render hogan templates at the command line.
Use it like: `hogan-render <mustache template file> <json data file>` e.g.

```bash
  $ hogan-render template.mustache data.json
```

Alternatively data can be read from STDIN e.g.

```bash
  $ cat data.json | hogan-render template.mustache
```

You can also run with just a template and type JSON into your terminal.
Use Ctrl+D (i.e. EOF) to have the data rendered.
