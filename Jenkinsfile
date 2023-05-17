pipeline {
    agent any

    environment {
        OWNER_NAME = "Maksim"
        PROJECT_NAME = "Main pipline =)"
    }

    stages {
        stage('1-Build') {
            steps {
                echo "Start of Stage Build"
                echo "Building......."
                
                echo "End of Stage Build"
            }
        }
        stage('2-Test') {
            steps {
                echo "Start of Stage Test"
                echo "Testing......."
                echo "End of Stage Build"
            }
        }
        stage('3-Deploy') {
            steps {
                echo "Start of Stage Deploy"
                echo "Deploying......."
                echo "End of Stage Build"
            }
        }
        stage('4-Print Name') {
            steps {
                echo "Hello master ${OWNER_NAME}"
                echo "Your project ->\"${PROJECT_NAME}\"<- is COMPLITED"
            }
        }
   }
}
