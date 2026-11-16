# Lab 05 - Git Flow and GitHub Actions

A small Python task manager with feature, release, and hotfix merge history. The `main` branch contains stable releases, and `develop` is the integration branch.

```sh
python -m unittest discover -s tests -v
git log --all --graph --oneline --decorate
```

GitHub Actions runs the unit tests on pushes to `main`, `develop`, and `feature/**`, and on pull requests into `develop`.
