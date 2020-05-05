# `takemeto`

TakeMeTo lets you add and open browser shortcuts from your command line.

As developers we always keep switching between docs in the browser and our IDE. Take Me To (TMT) helps you open pages directly from the terminal so you don’t have to manually open the browser and navigate to the page. This greatly improves the workflow for a developer.

Suppose I frequently visit some docs, say  [Vue.js Docs](https://vuejs.org/v2/guide/). Normally I would open my browser - Google ‘vue docs’ and open the docs link - takes a lot of time and there is a good chance you might even get distracted by something in the process (YouTube ahem ahem).

But with TMT - you can open the docs directly from the terminal.

## How it works with an example: 
Install takemeto:

```bash
pip3 install takemto
```

> TakeMeTo requires Python version > 3.7. Binaries for easier installation on all operating system has been planned.

Add a destination / bookmark or whatever you would like to call it. I prefer to call it a destination:

```bash
takemeto add vue-docs "https://vuejs.org/v2/guide/"
```

And then you can use the following command to take you to Vue Docs right from your terminal:

```bash
takemeto dest vue-docs
```

There are similar commands to remove, update and list destinations. 

This is a tiny package I made to save myself time as I keep switching between docs and IDE a lot. This saves a lot of time and increases productivity. I hope it does the same for you. 

Any reviews and code contributions are most welcome!

Documentation for TMT is available on [GitHub](https://github.com/codegabru/takemeto). 

**Usage**:

```console
$ takemeto [OPTIONS] COMMAND [ARGS]...
```

**Options**:

* `--install-completion`: Install completion for the current shell.
* `--show-completion`: Show completion for the current shell, to copy it or customize the installation.
* `--help`: Show this message and exit.

**Commands**:

* `add`
* `dest`
* `list-all`
* `remove`
* `update`

## `takemeto add`

**Usage**:

```console
$ takemeto add [OPTIONS] NAME DESTINATION
```

**Options**:

* `--help`: Show this message and exit.

## `takemeto dest`

**Usage**:

```console
$ takemeto dest [OPTIONS] NAME
```

**Options**:

* `--help`: Show this message and exit.

## `takemeto list-all`

**Usage**:

```console
$ takemeto list-all [OPTIONS]
```

**Options**:

* `--help`: Show this message and exit.

## `takemeto remove`

**Usage**:

```console
$ takemeto remove [OPTIONS] NAME
```

**Options**:

* `--help`: Show this message and exit.

## `takemeto update`

**Usage**:

```console
$ takemeto update [OPTIONS] NAME DESTINATION
```

**Options**:

* `--help`: Show this message and exit.

Built with [Typer](https://typer.tiangolo.com/) 🔥