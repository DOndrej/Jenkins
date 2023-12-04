pipeline {
    agent any

    parameters {
        string(defaultValue: "TEST", description: "Which enviroment to deploy in", name: "deployEnv")

    }
    stages {
        stage("Demo") {
            steps {
                echo "string is set to: ${params.deployEnv}"

            }
        }
    }
}