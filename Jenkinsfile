pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name jenkins-node2-stack --template-body file://sampleec2.json --region 'us-west-2'"    
              }
             }
            }
            }
