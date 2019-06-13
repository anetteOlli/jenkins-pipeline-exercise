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
        
                echo 'after gradle-thingy'
            }
        }
        stage('Results') {
            steps{
                echo 'Results'
            }
        }
    }
}
