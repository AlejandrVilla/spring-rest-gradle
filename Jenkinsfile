pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                sh 'java -version'
                sh 'gradlew bootRun'
            }
        }
        stage("test"){
            steps{
                echo "test"
            }
        }
    }
}