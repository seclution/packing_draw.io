# draw.io

Provides packaging for the [draw.io](https://www.draw.io) diagramming library. The generated packages are used by the [Diagram Application](https://github.com/xwiki-contrib/application-diagram/).

* Project Lead: [Marius Dumitru Florea](http://www.xwiki.org/xwiki/bin/view/XWiki/mflorea)
* License: **Apache 2.0** license. Note that the packaged code (the draw.io library developed by JGraph Ltd) and some classes we modified (also developed by JGraph Ltd)  are licensed under Apache 2.0.
* Continuous Integration Status: [![Build Status](http://ci.xwiki.org/job/XWiki%20Contrib/job/draw.io/job/master/badge/icon)](http://ci.xwiki.org/view/Contrib/job/XWiki%20Contrib/job/draw.io/job/master/)

## Vendor submodule

The `vendor` directory stores [jgraph/drawio](https://github.com/jgraph/drawio) as a Git submodule.
A manual GitHub Actions workflow (`update-drawio-submodule.yml`) can be triggered
from the **Actions** tab to add or update this submodule. The workflow creates
the `vendor` folder if needed, adds the submodule when missing and checks out
the latest available tag of the draw.io repository each time it runs, committing
the change automatically.
