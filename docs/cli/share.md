share
=====

Shares your local site publicly.

This is useful for sharing work with clients or testing your local site on multiple devices. The user is *required* to specify the `url` they want to share using the `--url` or `-u` flag. This `url` must be of the form `http://localhost:port`.

SSL is provided via `localtunnel`, the underlying technology lando uses to share local `urls`.

> #### Hint::What URL to use
>
> Try running `lando info` from inside your app. Any service with a `http://localhost:port` address should be shareable.

Usage
-----

```bash
lando share -u http://localhost:32785
```

Options
-------

```bash
--clear        Clears the lando tasks cache
--lando        Show help for lando-based options
--url, -u      Url to share. Needs to be in the form http://localhost:port
--verbose, -v  Runs with extra verbosity
```
