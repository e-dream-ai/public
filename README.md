# e-dream client releases

see the [releases](https://github.com/e-dream-ai/public/releases).

## procedure to make a release

* In the client repository, tag the code and build the release images
  (zip files).

* In this public repository, apply the same tag.

* Make a release with the github button, write the notes, and upload
  the images. If this is a pre-release, click that box to mark that,
  and you are done. Otherwise, continue with linking as described
  below.

* Update the link to the current release in the *main branch* of the
  frontend repository by editing `APP_VERSION` in
  `src/components/pages/install/install.page.tsx`

* Push and that's it, Github and Netlify build automation should make
  the change live in a few minutes.
