# .github

Org-wide defaults for the Farmalogg-AS repos. GitHub uses each file here for every repo in the org that has no file of
that type of its own (see GitHub's
[default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)).
So any supported file you add here applies to every repo that lacks one. GitHub requires this repo to be public, so it
holds no secrets, infrastructure names or business logic.

## Files

- `CONTRIBUTING.md` — points to the workspace repo's `CONTRIBUTING.md`. GitHub links to it when you open a PR or an
  issue.
- `pull_request_template.md` — the PR description GitHub pre-fills when you open a PR on github.com. Its last comment
  has the rules for filling it in.

In the [workspace repo](https://github.com/Farmalogg-AS/root), this repo is cloned as `dot-github`, since the
workspace has a `.github` folder of its own.
