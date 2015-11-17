# npm-shell-debug

Debug the shell that NPM launches to run your `scripts`.

On `postinstall`, this package runs:

```sh
which sh
echo $SHELL
echo $SHELLOPTS
shopt
```

If you're experience any errors when running something in `scripts`, or when
you install a package that runs `postinstall`, then installing this package
might help you debug why the `script` is broken.
