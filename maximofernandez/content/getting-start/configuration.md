+++
title = "Configuration"
description = ""
weight = 2
+++

When building the website, you can set a theme by using `--theme` option. We suggest you to edit your configuration file and set the theme by default. Example with `config.toml` format.
<!--more-->

Import sample config from sample site to Hugo root:

```
$ cp themes/docdock/maximofernandez/config.toml .
```

Change following `config.toml` line as needed, depending on method above:
```
theme = "<hugo-theme-docdock-dir-name>"
```
Comment out following line, so default `themes/` will be used:

```
# themesdir = "../.."
```


{{%excerpt%}}
## Activate search

If not already present, add the follow lines to the `config.toml` file.

```toml
[outputs]
home = [ "HTML", "RSS", "JSON"]
```
{{% /excerpt%}}


LUNRJS search index file will be generated on content changes.

#### (Bonus)
Create empty file `.gitkeep` inside `public/` and add following to `.gitignore`.  This way it will keep repo smaller and won't bring build result files and errors to remote checkout places:
```
/public/*
!/public/.gitkeep
```

### Preview sites
```
$ hugo server
```
to browse site on http://localhost:1313

## Your website's content

Find out how to [create]({{%relref "si/_index.md"%}}) and [organize your content]({{%relref "content-organisation/_index.md"%}}) quickly and intuitively.

Find out how to [create]({{%relref "ud2/_index.md"%}}) and [organize your content]({{%relref "content-organisation/_index.md"%}}) quickly and intuitively.
