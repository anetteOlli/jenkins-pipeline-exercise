pipeline {
    agent any
    
    stages {
        stage('greetings') {
            steps{
                echo 'Holla Mundos!'
            }
        }
        stage('Preparation') {
            steps{
                echo 'Preparation'
            }
        }
        stage('Build'){
            steps{
                echo 'Build'
                ./gradlew clean test jar
            }
        }
        stage('Results') {
            steps{
                echo 'Results'
            }
        }
    }
}
