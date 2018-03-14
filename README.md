# antonmdev/fx Docker Wrapper
This repo simply wraps https://github.com/antonmedv/fx in a convenient Docker image.

## Alias
Creating an alias like
```shell
alias fx='docker run --rm -i matthewadams12/fx fx'
```
is pretty darned convenient.

### Run with alias
```shell
$ echo '"foo"' | fx this
"foo"
$ echo '{"foo":"bar"}' | fx this.foo
"bar"
```
etc...
