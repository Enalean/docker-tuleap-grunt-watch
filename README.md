# Docker image to launch a simple Tuleap Grunt Watch

## How to use

In order to execute tests, all you have to do is to execute this command:

    $ docker run --rm=true -ti -v $PWD:/tuleap erwyn/tuleap-grunt-watch --path PathToFolderContainingGruntFile
