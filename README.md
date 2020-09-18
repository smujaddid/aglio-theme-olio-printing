# aglio-theme-olio-printing-nav
a printable olio-based theme (with attributes instead of schema)

Daniel Taylor's [aglio](https://github.com/danielgtaylor/aglio) tool is a nice
renderer for API Blueprints. Aglio comes with a handsomely-styled theme called
[olio](https://github.com/danielgtaylor/aglio/tree/olio-theme#readme). This
repo contains a modified version of [olio-attributes](https://github.com/hajimeni/aglio-theme-olio-attributes)
for printing. Changes:

- @hajimeni's changes in https://github.com/hajimeni/aglio-theme-olio-attributes to add attributes to the aglio output
- @BenGardiner's changes in https://github.com/BenGardiner/aglio-theme-olio-printing to add attributes to the aglio output
- added back nav
- allow non-full width for default template
- added back the back to top floater
- remove table of contents to the output for default template
- always show resources title
- preserve original body contents in action section [@Gasol aglio-theme-olio](https://github.com/Gasol/aglio-theme-olio/commit/1d5c1775b07b139aeecb3e5c4852b3b35bcd9a4d)

# Quickstart

```bash
$ sudo npm install -g aglio
$ sudo npm install -g aglio-theme-olio-printing-nav
$ aglio -t olio-printing-nav -i blueprint.apib -o MyAPI.html
```

# Original License

Aglio[https://github.com/danielgtaylor/aglio]

Copyright &copy; 2016 Daniel G. Taylor

http://dgt.mit-license.org/

# Acknowledgements

This package is incremental changes on top of [@hajimeni aglio-theme-olio-attributes](https://github.com/hajimeni/aglio-theme-olio-attributes)

This package is incremental changes on top of [@BenGardiner aglio-theme-olio-printing](https://github.com/BenGardiner/aglio-theme-olio-printing)

This package also referencing changes from [@onlicar aglio-theme-onlicar](https://github.com/onlicar/aglio-theme-onlicar) which is [this commit](https://github.com/onlicar/aglio-theme-onlicar/commit/8fa8005dacf95853788bb082de88e2a7ce4baaec)

This package also referencing changes from [@Gasol aglio-theme-olio](https://github.com/Gasol/aglio-theme-olio) which is [this commit](https://github.com/Gasol/aglio-theme-olio/commit/1d5c1775b07b139aeecb3e5c4852b3b35bcd9a4d)

This packages (as changes to @BenGardiner aglio-theme-olio-printing) was developed with support from the [National Motor Freight Traffic Association](http://www.nmfta.org) to produce standalone documentation for the [Open Telematics API](https://github.com/nmfta-repo/nmfta-opentelematics-api)
