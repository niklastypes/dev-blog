# niklasbaier.gitlab.io

Static personal website using [Hugo](https://gohugo.io/) and the [Blowfish](https://github.com/nunocoracao/blowfish) theme.
Deployed via GitLab pages to https://niklasbaier.gitlab.io/.

## Requirements

To run the web server:
```bash
brew install hugo
```

## Setup

As this project is using Blowfish as a git submodule, run the following once:

```bash
git submodule update --init --recursive
```

Then, start up the web server locally via

```bash
hugo server
```

and view on http://localhost:1313/.

## Color scheme

The Blowfish theme has been customized to follow the [Congo](https://github.com/jpanther/Congo) theme color scheme.
The respective `img/backgrounds/*.svg` assets have been adapted as follows:

```
#5e6fa3 -> #6d40d9
#689cc5 -> #b99af4
#93dbe9 -> #e2d4ff
```

The respective `img/featured/*.svg` assets have been adapted as well:

```
#48cae4 → #6d40d9
#03045e -> #5a2fc7
#023e8a -> #6d40d9
#0077b6 -> #8b5de8
#0096c7 -> #b99af4
#00b4d8 -> #b99af4
#90e0ef -> #d1b9f8
#ade8f4 -> #e2d4ff
#caf0f8 -> #f0e8ff
```