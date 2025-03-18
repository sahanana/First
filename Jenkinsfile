pipeline {
    agent any

    stages {
        stage("Build_stage") {
            steps {
                echo 'Building projects....'
            }
        }
        stage("Test_stage") {
            steps {
                 echo "Testing Project..."
            }
        }
        stage("Deploy-stage"){
            steps{
                echo "Deploying Project..."
            }
        }
     
    }
       post {
            always {
                echo "Thank you.."
            }
        }
}
