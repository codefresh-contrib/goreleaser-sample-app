# Using Goreleaser inside Docker with Codefresh

[Goreleaser](https://github.com/goreleaser/goreleaser) is a help utility that easily allows to create

* Binary packages for each OS/arch
* Archives
* Github releases
* Docker images
* Snap/RPM/deb/Homebrew

for Go applications.

There is already a [Docker image for Goreleaser](https://hub.docker.com/r/goreleaser/goreleaser/) so it is very easy to use it in Codefresh pipeline.

## Prerequisites

1. Create a [free Codefresh account](https://codefresh.io/docs/docs/getting-started/create-a-codefresh-account/)
1. Fork this project in your Github account


## Create Codefresh pipeline

To use Goreleaser with Codefresh

1. Create a new pipeline
1. Add the [pipeline content](codefresh.yml)
1. Edit the pipeline with your own github integration (instead of `github-1`)

Make sure that you set the [trigger](https://codefresh.io/docs/docs/configure-ci-cd-pipeline/triggers/) to happen only for git tags.

That's it! Run the pipeline to see it in action.


Enjoy!

