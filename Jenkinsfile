pipeline {
    agent any

    environment {
      DISABLE_AUTH = 'true'
      DB_ENGINE = 'sqlite'
    }
        stages {
            stage('Build') {
                steps {
                    input("go ahead?")
                }
            }
        }
}