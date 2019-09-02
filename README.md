# GithubActions-Docker

Simple example of extending the Docker CLI and using GitHub Actions to build/test.

The workflow can be found [here](.github/workflows/workflow.yml)

The workflow runs when a push is made to master.  The GithubActions VM, which is spun up when the workflow starts, has it's docker version updated and the plugin is then setup.
