# git

This example demonstrates hosting a bare `git` repository over "dumb" HTTPS
using [Now](https://now.sh)'s "static file" hosting.

There's a `test.git` repository hosted that has a single `test.txt` file inside.
You can clone the repo locally using something like:

```bash
$ git clone https://now-examples-git.now.sh/test.git
```

Since's Now deployments have a read-only filesystem, this example is only useful
for read-only Git repositories. Mostly for demonstration and testing purposes.

## How to deploy

First, [download `now`](https://zeit.co/download). Then, clone this
repository and run `now`:

```bash
$ git clone git://github.com/now-examples/git
$ cd git
$ now
```

> Example: `https://now-examples-git.now.sh`

## License

MIT
