pipeline {
    agent {
        node{
            label "linux && java11git "
        }
    }
    stages {
        stage("Hello") {
            steps {
                echo("Hello PIpeline")
            }
        }
    }
}