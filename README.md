# `gh-edit`

Edit Issues, PRs, Comments, and Gists locally

If you spend a lot of time typing on GitHub and miss the comfort of your own
editor, I feel you.

This is why I wrote this little script, it syncs-on-save a local file with a
PR/Issue/Comment/Gist.

Current support:

- Issue
    - https://github.com/owner/repo/issues/123
    - https://github.com/owner/repo/issues/123#issuecomment-456
- PR
    - https://github.com/owner/repo/pull/123
    - https://github.com/owner/repo/pull/123#issuecomment-456
    - https://github.com/owner/repo/pull/123#discussion_r456
- Gist
    - https://gist.github.com/owner/123

See more in [`./gh-edit`](./gh-edit) or with `gh edit -h`.
