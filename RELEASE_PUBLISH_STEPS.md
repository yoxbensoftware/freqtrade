# GitHub Release Publish Steps

Use this file when creating a GitHub release for the local Gate.io setup snapshot.

## Recommended tag

Use the existing tag:

```text
gateio-local-setup-v1
```

## Release title

```text
Gate.io Local Setup v1
```

## Release description

Copy the contents of:

```text
RELEASE_GATEIO_LOCAL_SETUP.md
```

into the GitHub release description box.

## Suggested steps

1. Open the repository releases page on GitHub.
2. Click `Draft a new release`.
3. Select tag `gateio-local-setup-v1`.
4. Set the release title to `Gate.io Local Setup v1`.
5. Paste the contents of `RELEASE_GATEIO_LOCAL_SETUP.md`.
6. Publish the release.

## Notes

- The live `user_data/config.json` file is not part of the repository.
- Only the sanitized example configs should be referenced in release material.