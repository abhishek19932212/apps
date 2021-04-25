pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation deploy --template-file ./sampleec2.json --stack-name my-new-stack --parameter-overrides file://parameters.json --region 'us-west-2'"    
              }
             }
            }
            }
