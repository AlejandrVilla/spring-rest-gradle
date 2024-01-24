pipeline{
    agent any
    stages{
        stage("version"){
            steps{
                sh 'java -version'
                
            }
        }
        // stage("test"){
        //     steps{
        //         echo "test"
        //         sh './gradlew assemble'
        //     }
        // }
        stage("build"){
            steps{
                sh './gradlew bootRun'
            }
        }
    }
}