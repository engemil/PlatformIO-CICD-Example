![example workflow](https://github.com/strooom/demoCloudBuilds/actions/workflows/testbuildrelease.yml/badge.svg)
[![codecov](https://codecov.io/gh/Strooom/demoCloudBuilds/branch/develop/graph/badge.svg?token=KYQ9MM7TA6)](https://codecov.io/gh/Strooom/demoCloudBuilds)

repository containing a template for a PlatformIO project
Demonstrating:
* automatic 'semver' version with build timestamp and commit hash
* unit testing, locally as well as in the cloud with github actions. Test coverage with GCOV extension
* builds, locally as well as in the cloud with github actions. Test coverage reports on codecov.io
* stores .bin file as artifact of workflow run
* stores .bin file and source.zip with a new release


**Extra note:** If problem with building `target_application` with a new repository, just add your first tag with `git tag v0.0.1` (or whatever number you prefer).

<!--Test-->