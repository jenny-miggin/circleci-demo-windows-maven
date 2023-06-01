# CircleCI Demo - Java App built using Maven on Windows

This repo contains an example of how to build a Java application using maven on a Windows executor

## How it works

- The Windows executor already comes with [OpenJDK installed](https://circleci.com/developer/machine/image/windows-server-2022-gui), however maven does need to be installed as part of the job so this is done via Chocolatey
- If the tests can be executed on a Docker container, then the [maven orb](https://circleci.com/developer/orbs/orb/circleci/maven#jobs-test) can be helpful. Some of the source code was used to split tests in this project.
