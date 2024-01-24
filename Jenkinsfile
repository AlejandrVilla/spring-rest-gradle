pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                sh 'gradlew bootRUn'
            }
        }
        stage("test"){
            steps{
                echo "test"
            }
        }
    }
}