# DockerJenkinsWithGitBuildAgent

The initial maestrodev/build-agent has a /usr/var/maestro-agent/.m2/settings.xml which causes Maven to use a repository located at http://localhost:8082/archiva/repository/all.

This image removes this file, so Maven downloads artifacts from the Central repository.

Use this with the andrewgorton/dockerjenkinswithgit Jenkins image.
