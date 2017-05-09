## gliderlabs/ci

CI environment for Glider Labs projects on CircleCI.

Merges to master are pushed to [gliderlabs/ci](https://hub.docker.com/r/gliderlabs/ci) on Docker Hub.

Note that previously this lived in [infra.gl](https://github.com/gliderlabs/infra.gl), so tags exist for `build-60` to `build-67`. This repository starts build numbers over, so before a new `build-60`, be sure no projects are on those tags and delete them on Docker Hub.

Future optimization: tags for special scenarios to keep image as small as possible for most projects using it.
