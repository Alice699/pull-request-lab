# Co-authored commits

This guide documents the commit metadata used in the lab's two-account workflow experiment. It does not imply that the accounts represent different people.

## Record both accounts

The primary author of this documentation commit is Alice699. The commit message also records biawakLahat with this trailer, separated from the subject by an empty line:

```text
docs: document co-authored commits and completed merge

Co-authored-by: biawakLahat <136351960+biawakLahat@users.noreply.github.com>
```

Use an email associated with the co-author's GitHub account. This experiment uses the account's GitHub-provided no-reply address.

For a shared change made locally, the equivalent command is:

```sh
git commit -m "docs: document a shared change" \
  -m "Co-authored-by: biawakLahat <136351960+biawakLahat@users.noreply.github.com>"
```

## Review and merge

1. Open the commit on GitHub and confirm that Alice699 and biawakLahat are both linked as authors.
2. Review the documentation changes in the pull request.
3. While signed in as biawakLahat, use **Create a merge commit** to preserve the original co-authored commit.
4. Record the merged PR URL and check the profile separately for Pair Extraordinaire.

Co-author attribution and an achievement appearing are separate observations. The badge outcome remains pending until it is observed.

See [GitHub's co-author documentation](https://docs.github.com/en/pull-requests/how-tos/commit-changes/creating-a-commit-with-multiple-authors) for the trailer format.
