Apache Maven Skip Demo
======================

Simple demonstration of how to skip plugin executions in a Apache Maven build.

By default a build will update the version number and commit/push it to git:

    $ mvn compile

You can skip updating the version number and committing/pushing by activating the *skipVersionBump* profile:

    $  mvn compile -PskipVersionBump
