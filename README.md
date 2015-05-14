# DockerJenkinsWithGitBuildAgent

The [maestrodev/build-agent](https://registry.hub.docker.com/u/maestrodev/build-agent/) has a /usr/var/maestro-agent/.m2/settings.xml which directs Maven to use a repository located at http://localhost:8082/archiva/repository/all.

This image removes this file, so Maven downloads artifacts from the Central repository.

Use this with the [andrewgorton/dockerjenkinswithgit](https://registry.hub.docker.com/u/andrewgortonuk/dockerjenkinswithgit/) Jenkins image.

Blog post about it [here](http://www.andrewgorton.uk/blog/maven-inside-dockerd-build-agents/).
