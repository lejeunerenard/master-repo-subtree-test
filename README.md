# Master Repo Subtree Test

This is a test of combining separate repositories as a single master repository
which references branches of the slave as folders for easy navigation across
multiple repositories. This test uses subtree to reference branches from
slave repositories.

## Branches

- [`day-1`](day-1)
- [`day-2`](day-2)
- [`day-3`](day-3)
- [`day-4`](day-4)

## Notes

Doesn't provide links to the slave repositories like submodules do. But it is
much smaller to clone down because it squashes the changes into a single commit
but makes reference to the commits in the slave repository in the squashed
commit. That way it can track the changes as necessary.
