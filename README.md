# `Jenkins CLI Wrapper` - Better than typing java -jar and everything else


## Setting Up

1.  Place the jenkins-cli script into your path
2.  Place the jenkins-cli.jar file anywhere you want
3.  Run the script, it will check for the following:
    1. If .jenkins.creds does not exist, it will create it and ask for your username and api key
        1.  Get your API Key at `$JENKINS_SERVER/me/configure`
    2. If jenkins-cli.jar is in the same directory as the script or in your path.  If not, it will ask for the path.

## Running the utility
1. `jenkins-cli list-jobs`

## Roadmap
1. Pure bash helpers to help parse items
2. Pure bash REST requests for operations that the CLI tool does not support
