# Github Actions Workflow Templates

This is my collection of shared github actions workflows I use for my projects.

For Ansible Galaxy you may want to set `github_branch` to main if you don't use the `master` in `meta/main.yml`:

```yaml
galaxy_info:

  # Optionally specify the branch Galaxy will use when accessing the GitHub
  # repo for this role. During role install, if no tags are available,
  # Galaxy will use this branch. During import Galaxy will access files on
  # this branch. If Travis integration is configured, only notifications for this
  # branch will be accepted. Otherwise, in all cases, the repo's default branch
  # (usually master) will be used.
  github_branch: main
```
