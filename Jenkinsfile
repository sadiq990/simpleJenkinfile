pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                echo "========executing build========"
            }
        }
         stage("test"){
            steps{
                echo "========executing test========"
            }
        }
         stage("deploy"){
            // when {
            //     expression {
            //         BRANCH_NAME == 'master'
            //     }
            // }
            steps{
                echo "========executing deploy========"
            }
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}