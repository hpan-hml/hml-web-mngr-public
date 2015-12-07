Web Presence Management for Hardpan Media Library - GitHub Public Site
======================================================================
(HML::WEB::GH::MNGR::PUBLIC)
----------------------------

# Project Overview

## Availability

**Primary Source Code Repository:** [github:hpan-hml/hml-web-mngr-public][repro]

**License:** [COPYRIGHT](./COPYRIGHT) ([Original Text][ccby4])

# Design Notes

## Overview - Thesis

This project (`hml-web-mngr-public`) represents a manner of a
_management layer_ for the  [Hardpan Media Library Web Presence -
GitHub Project Group Hosting][hml-io] project (`hml-web-github-site`).

The _source tree_ of the `hml-web-github-site` project is managed as a
Git _submodule_ of the `hml-web-mngr-public` source tree. This permits
for manner of _source code management_ to be applied to the `site`
source tree -- namel, as within the `mngr-public` source tree --
moreover, without the contents of any single _management tools_
affecting the contents of the `site` source tree.

## Overview - Topical 

### Site Theme - Origins and Licensing

The [`hml-web-github-site`][hml-io] web site is developed in
application of a _responsive_ hypermedia content _theme_ published 
simultaneously by [HTML5 Up][html5up] and [Pixelarity][pixl]. The
_theme_ media files as published by [HTML5 Up][html5up] are provided
from [HTML5 Up][html5up] to _theme_ media file users, under terms of a
(_Creative Commons Attribution 3.0 Unported+_)[cc3] license. The same
theme media files may be licensed via [Pixelarity][pixl], for
applications under stipulations distinct to those provided under the
(_Creative Commons Attribution 3.0 Unported_)[cc3] license.

For purpose of allowing for redistribution of the theme media files
via a _public_ hosted source code repository, Hardpan Media Library
here applies an adapted version of the original [HTML5 Up][html5up]
_TXT_ theme. This project adapts the exact media files developed of
the theme, as those media files being licensed under terms  of the
(_Creative Commons Attribution 3.0 Unported_)[cc3] license. The
_adapted files_ -- together with any number of _added files_, created
for purpose of managing the content and presentation of the site --
are contained, as local to the source code repository, under the
filesystem directory [`src/theme/theme-txt/`][theme-txt].

Revisions to the original media files may reviewed via the
[GitHub][gh] web presentation system, Online, or via a local Git
client such as `git-cola`, then applied as to a _checked out_ edition
of the _baseline_ source code repository. 

[repro]: https://github.com/hpan-hml/hml-web-mngr-public
[ccby4]: http://creativecommons.org/licenses/by/4.0/legalcode
[hml-io]: https://github.com/hpan-hml/hpan-hml.github.io
[html5up]: http://html5up.net/
[pixl]: http://pixelarity.com/
[cc3]: http://creativecommons.org/licenses/by/3.0/
[theme-txt]: ./src/theme/theme-txt/
[gh]: http://www.github.com/
