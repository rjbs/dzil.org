# dzil.org, the Dist::Zilla site

This repository contains the content and build scripts for https://dzil.org the
homepage of Dist:Zilla.

The site content is in the `./src` directory, as a collection of Pod documents
and just a little HTML and CSS.  The Pod is written to be put together by
[Pod::CYOA](https://metacpan.org/pod/Pod::CYOA), but if you just look at the
files in your editor, it's probably clear.

You can build the site locally with `./bin/build-site`

It's built automatically by GitHub Actions and hosted on GitHub Pages.
