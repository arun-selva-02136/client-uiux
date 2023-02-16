pipeline {
    agent any
    stages {
        stage('clone') {
         
   steps {
                git branch: 'master', url: 'https://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@github.com/arun-selva-02136/client-uiux.git'
            }
        }
        stage('Build') { 
            steps { 
                echo "build success"
            }
        }
        stage('push to ECR') {
            steps {
                echo "deploy success"
            }
        }
        stage('delete local inages') {
            steps {
               echo "delete success"
            }
        } 
    
    }
}
