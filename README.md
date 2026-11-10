# devicetree-rebasing mirror

Mirror of
<https://git.kernel.org/pub/scm/linux/kernel/git/devicetree/devicetree-rebasing.git>,
used as a submodule by PebbleOS so that its builds do not depend on the
availability of that host.

`master` and the tags are upstream's, untouched. This branch, `mirror`, only
holds the workflow that syncs them once a week; it can also be run by hand
from the Actions tab.
