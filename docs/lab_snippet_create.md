## lab snippet create

Create a personal or project snippet

### Synopsis


Source snippets from stdin, file, or in editor from scratch
Optionally add a title & description with -m

```
lab snippet create [remote] [flags]
```

### Options

```
  -h, --help              help for create
  -m, --message strings   Use the given <msg>; multiple -m are concatenated as separate paragraphs (default [-])
  -n, --name string       (optional) Name snippet to add code highlighting, e.g. potato.go for GoLang
  -p, --private           Make snippet private; visible only to project members (default: internal)
      --public            Make snippet public; can be accessed without any authentication (default: internal)
```

### Options inherited from parent commands

```
  -g, --global   create as a personal snippet
```

### SEE ALSO

* [lab snippet](lab_snippet.md)	 - Create a personal or project snippet

###### Auto generated by spf13/cobra on 18-Dec-2019
