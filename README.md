# minimal-grey-firefox

A minimalist, grey Firefox theme.

Mozilla's [manifest.json documentation](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json).

## Releasing new versions

The release process is quite manual at the moment. New versions are released by doing the following:

1. Changing the `src/manifest.json` file.
2. Committing to `main`.
3. Create an _annotated_ git tag on main to the commit to release.
4. Let the pipeline build a zip.
5. Download the zip and use it to publish on Firefox manually.
