pipeline {
    agent any

    parameters {
        choice(choices: ["TEST", "DEV", "PREPROD", "PROD"], description: "Which enviroment to deploy in", name: "deployEnv")

    }
    stages {
        stage("Demo") {
            steps {
                echo "choice is set to: ${params.deployEnv}"

            }
        }
    }
}
