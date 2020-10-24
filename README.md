# kivy-website-docs

This repo holds the generated docs for https://github.com/kivy/kivy/, that is hosted on
kivy.org.

Kivy docs are generated on its CI, and if its branch name also exists on this
repo with a `docs-` prefix, then the CI will push the generated docs to
its corresponding branch here. E.g. This repo has a `docs-stable` branch,
so any docs generated for kivy's `stable` branch will be pushed to
`docs-stable` here.

All the `docs-xxx` branches from this repo are then displayed on kivy.org, except
for `docs-test-docs`. To test the docs generation and automatic push, use or create
a kivy branch named `test-docs` and it won't be displayed on the site, but you can
see the changes in the branch here.
