pipeline {
    agent any
    
    stages {
        stage('Preperation') {
            steps{
                echo 'prep!'
            }
        }
        stage('Build') {
            steps{
                echo 'buld'
		sh "./gradlew clean test jar"
            }
        }
        stage('Results') {
            steps{
                echo 'Res'
            }
        }
    }
}
