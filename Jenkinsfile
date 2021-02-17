pipeline {
    agent any
    stages {
        stage('One') {
            steps {
                build "SampleDesignJob"
            }
        }
        stage('TWO') {
            steps {
                build "SampleBuildJob"
            }
        }
        stage('Three') {
            steps {
                build "SampleDeployJob"
            }
        }
        stage('Four') {
            steps {
                build "SampleTestJob"
            }
        }
    }
}