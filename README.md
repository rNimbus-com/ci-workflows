# ci-workflows
Reusable workflows for Continuous Integration.

## release.yml

Calculates next release versions from code comments via the [codacy/git-version](https://github.com/codacy/git-version) marketplace action. See the [Version Modeling](https://github.com/codacy/git-version/blob/master/README.md#versioning-model) section of their readme for details.

Creates a GitHub Release and tag from the above version, and adds additional Major (v#) and Minor (v#.#) tags to your repository.
