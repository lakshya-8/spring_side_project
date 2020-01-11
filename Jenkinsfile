pipeline{
    agent any
    tools{
        maven "maven-3.3.9"
    }
    stages{
        stage('Build Java'){
            steps{
                sh 'mvn compile'
            }
        }
        stage('Tests'){
            steps{
                sh 'mvn test'
            }
        }
    }
}