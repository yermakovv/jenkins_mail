pipeline {
    agent any
     stages {
        stage('Send') {
            steps {
 
     mail to: 'idzeland@gmail.com',
     subject: "Job '${env.JOB_NAME}' (${env.BUILD_NUMBER}) is waiting for input",
     body: "Please go to ${env.BUILD_URL}."
     }
    }
   
          stage('Echo') {
             steps {
                 echo "Hello"
             }
          }
     }
 }
