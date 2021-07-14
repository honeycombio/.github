---
name: Make repo public
about: Checklist to verify repo is ready to be public
title: Make repo public
labels: ''
assignees: ''

---

* [ ] Git history reviewed -- ensure no weirdness was committed
* [ ] Access Rights
  * Owner team → Admin
  * Engineering → Write
  * Honeycombers → Triage
  * houndtravisci → Write (if going to create GH releases via CI)
* [ ] License --> The default license is Apache-v2
* [ ] Main branch --> primary branch should be named `main`
* [ ] Merge commits & deleting merged branches
  * Merge button --> Allow squash merging
  * Merge button --> Automatically delete head branches
* [ ] Branch protection
  * Require pull request reviews before merging - 1 minimum
  * Require review from Code Owners
  * Require status checks to pass before merging
    * Build status check
  * Include administrators
* [ ] codeowners
* [ ] changelog
* [ ] .editorconfig file
* [ ] github actions apply project labels
* [ ] ci badge in readme
