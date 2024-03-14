# Gitlab Pipeline Templates

This is a collection of [Gitlab CI/CD](https://docs.gitlab.com/ee/ci/index.html) pipeline templates.

More information on Gitlab CI/CD pipeline templates in general:

- [Developing Templates](https://docs.gitlab.com/ee/development/cicd/templates.html)
- [Example Templates](https://docs.gitlab.com/ce/ci/examples/index.html#cicd-templates)

# Templates

## Docker - Simple([docker/simple.yml](./docker/simple.yml))

Provides pipeline templates for building / publishing Docker images to Gitlab Container Registry using docker-in-docker builders (deprecated, use Kaniko)

## Kaniko ([docker/kaniko.yml](./docker/kaniko.yml))

Builds multi-arch container images without a running Docker daemon using [Kaniko](https://github.com/GoogleContainerTools/kaniko)

## Crane Copy ([docker/crane-copy.yml](./docker/crane-copy.yml))

Copy images between container registries using [Crane](https://github.com/google/go-containerregistry/blob/main/cmd/crane/doc/crane.md)
