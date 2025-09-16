Faremeter's Public Website
--------------------------

This website uses [hugo](https://gohugo.io).  You can modify the CSS, themes, and settings, and adjust it however you'd like.  See the [hugo documentation](https://gohugo.io/documentation/) for more information.

It's currently very informal.  Just commit your changes (make sure they're actually ones you want live) and push your branch to GitHub's `main`.

0.  Setup your environment

On macOS you need homebrew.  To install hugo just do:

```
brew install hugo
```


1. Previewing content

```
hugo serve
```

and then browse to http://localhost:1313/

2. Publishing Content

`git add` your content, and then commit.  Once you've done that, run:

```
hugo build
```

and `git add` the contents of `public`.  Once you `git push` the `main` branch to GitHub, the site will automatically be published.
