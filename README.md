dotfiles.github.com
===================

Your _unofficial_ guide to doing dotfiles on GitHub.

Please visit [http://dotfiles.github.com](http://dotfiles.github.com).

## Contributing

If you'd like to contribute to this site, you'll need [nanoc](http://nanoc.stoneship.org/) the awesome static site generator from [Denis Defreyne](http://stoneship.org/).

This site is served from GitHub pages and the source resides in the [src folder](). Other than the usual [nanoc usage info](http://nanoc.stoneship.org/docs/), it's important to note:

* *Add exclusions for any root content not generated by nano.* This is done in the `src/config.yml` under `exclusions.` These exclusions won't get pruned for the `nanoc prune` command.
