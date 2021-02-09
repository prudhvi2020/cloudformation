pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ecinstance10 --template-body file://ec2.yaml"
              }
             }
            }
            }
