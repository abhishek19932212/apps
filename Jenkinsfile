pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2instance --template-body file://ec2-instance.yml --region 'us-west-2'"
              }
             }
            }
            }
