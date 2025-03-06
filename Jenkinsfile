@Library('my-shared-library') _

pipeline {
    agent any

    stages {
        stage('Demo') {
            steps {
                    myFunction('World')  // Calling the shared function
            }
        }
    }
}
