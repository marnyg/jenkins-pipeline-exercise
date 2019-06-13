pipeline {
    agent any
    
    stages {
        stage('Preperation') {
            steps{
                echo 'prep!'
		sh "./gradlew clean test jar"
            }
        }
        stage('Build') {
            steps{
                echo 'buld'
            }
        }
        stage('Results') {
            steps{
                echo 'Res'
            }
        }
    }
}
