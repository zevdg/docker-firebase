# docker-firebase

## Purpose

This image was created specifically for usage with continuous integration systems, and contains the minimum requirements to deploy a project to [Firebase](https://firebase.google.com/). Currently being used with [gitlab ci](https://about.gitlab.com/features/gitlab-ci-cd/), but should meet the requirements for most CI systems.

## Details

### Base Image

- [node 12 (carbon)](https://hub.docker.com/r/library/node/) - The current Node LTS image

### Additional Node Modules

- [Firebase CLI](https://github.com/firebase/firebase-tools) - The Firebase Command Line Tools. Required to deploy to Firebase.
