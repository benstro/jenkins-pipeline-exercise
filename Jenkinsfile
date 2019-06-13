pipeline {
    agent any
    
    stages {
        stage('greetings') {
            steps{
                echo 'Holla Mundos!'
            }
        }
        stage('Preperation') {
            steps{
                echo 'Preperation'
            }
        }
        stage('Build'){
            steps{
                echo 'Build'
                ./gradlew clean test jar
            }
        }
        stage('Results'){
            steps{
                echo 'Results'
            }
        }
    }
}