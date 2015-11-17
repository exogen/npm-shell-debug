# npm-shell-debug

Debug the shell that NPM launches to run your `scripts`.

On `postinstall`, this package runs:

```sh
which sh
echo $SHELL
echo $SHELLOPTS
shopt
```

If you're experiencing any errors when running something in `scripts`, or when
you install a package that has a `postinstall`, then installing this package
might help you debug why the command fails on your machine.
