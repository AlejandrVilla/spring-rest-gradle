pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                sh 'java -version'
                sh 'gradle bootRun'
            }
        }
        stage("test"){
            steps{
                echo "test"
            }
        }
    }
}