pipeline{
    agent any
    stages{
        stage("version"){
            steps{
                echo "test"
                sh 'java -version'
            }
        }
        stage("build"){
            steps{
                sh 'gradle bootRun'
            }
        }
    }
}