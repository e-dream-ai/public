# e-dream-ai/public — DEPRECATED

> [!WARNING]
> **This repository is deprecated and no longer in use.**
>
> It used to host client release artifacts for download, but that workflow has moved elsewhere and nothing in the Infinidream project points at this repo anymore. Do not publish new releases here. Do not link to it from other repos or from the website.

## Historical purpose

This repository was previously used to publish e-dream client release images (zip files) via GitHub Releases. The old procedure was:

1. In the `client` repository, tag the code and build the release images (zip files).
2. In this repository, apply the same tag.
3. Create a GitHub Release, write notes, and upload the images. Mark as pre-release if applicable.
4. Update `APP_VERSION` in `frontend/src/components/pages/install/install.page.tsx` on the main branch to point at the new release.
5. Push — GitHub and Netlify build automation would then make the change live.

That flow is no longer active. The historical [releases](https://github.com/e-dream-ai/public/releases) remain for archival purposes only.
