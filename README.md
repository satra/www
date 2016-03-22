Personal Website
----------------

[Click to go to Website](https://satra.cogitatum.org/www)
Note that you may receive a warning about a certificate. This is ok at the moment.

Uses the following [Solid](https://github.com/solid/solid) components.

```
git remote add solid-inbox git@github.com:solid/solid-inbox.git
git subtree add --prefix=inbox solid-inbox gh-pages
git remote add solid-timeline git@github.com:solid-social/timeline.git
git subtree add --prefix=timeline solid-timeline gh-pages
git remote add solid-plume git@github.com:deiu/solid-plume.git
git subtree add --prefix=blog solid-plume gh-pages
git remote add solid-profile git@github.com:linkeddata/profile-editor.git
git subtree add --prefix=profile solid-profile gh-pages
git remote add solid-docs git@github.com:linkeddata/dokieli.git
git subtree add --prefix=docs solid-docs master
```
