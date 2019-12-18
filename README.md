---
published: false
---

# Pokeballroom

If you'd like to use my list as a template:

1. [Fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) (or clone) this repo to your account
2. Change the title of your site in [line 2 of index.html](/index.html#L2) to whatever you want
3. Replace the contents of [list.yml](/_data/list.yml) with your Pokemon and their details, but keep the formatting the same
4. Publish your site through [GitHub Pages](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)


#### Notes on using sprites

The Pokemon and ball sprites will only work correctly if the `pokemon` and `ball` attributes are named correctly:

- The value of `pokemon` must be the species name.
- Sprites are based on the SWSH dex, so only those sprites will work.
- For some forms, such as Galar forms, you'll need to define which sprite to use by adding a separate line to the Pokemon's block. It should look something like  `sprite: ponyta-galar`. You can find the list of sprite css classes [here](/_sass/sprites.scss).
- The value of `ball` must be the name of the ball, but without "ball". For example, `ball: moon`.
